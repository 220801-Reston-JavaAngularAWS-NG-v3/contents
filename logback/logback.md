# Logback

**Content**

1\. Introduction to Logback

2\. Logback’s Core Features & Advantages

3\. Logback project

4\. Basic Setup

5\. Logback Configuration Files

6\. Logback Components

6.1 Appenders

*6.1.1 The Console Appender*

*6.1.2 The Rolling File Appender*

6.2 Layouts

6.3 Loggers

7\. References

# 1. Introduction to Logback

-   Logback is a logging framework for Java applications, created as a successor to the popular *log4j* project. In fact, both of these frameworks were created by the same developer.
-   Given that logging is a crucial part of any application for both debugging and audit purposes, choosing an adequate logging library is a foundational decision for any project.

## 2. Logback’s Core Features & Advantages

-   Faster execution compared to *log4j.*
-   Native support for *slf4j*, which makes it easy to switch to a different logging framework, should that be necessary later on.
-   Conditional processing of the defined configuration.
-   Advanced filtering capabilities.
-   Compression of archived log files.
-   Support for setting a maximum number of archived log files.
-   HTTP-access logging.
-   Recovery from I/O failures.

## 3. Logback project

The Logback project is organized in main 3 modules:

-   *logback-core* – contains the basic logging functionality
-   *logback-classic* – contains additional logging improvements, such as slf4j support
-   *logback-access* – provides integration with servlet containers, such as Tomcat and Jetty

## 4. Basic Setup

-   To start using the Logback, you first need to add the logback-classic dependency to the classpath. Let’s do that with Maven:

\<dependency\>

\<groupId\>ch.qos.logback\</groupId\>

\<artifactId\>logback-classic\</artifactId\>

\<version\>1.2.3\</version\>

\</dependency\>

-   This single dependency is enough, as it will transitively pull in the *logback-core* and *slf4j-api* dependencies.
-   **If no custom configuration is defined, Logback provides a simple, automatic configuration on its own.** By default, this ensures that log statements are printed to the console at DEBUG level.
-   Consequently, you can now obtain a *Logger* instance and start writing log messages using the default, basic config.
-   First, you can create a *Logger* by using the *slf4j LoggerFactory* class:

**private static final Logger logger = LoggerFactory.getLogger(UserServiceTest.class);**

-   Next, you can use the typical logging APIs corresponding to the log level:

**logger.debug("UserService Test");**

## 5. Logback Configuration Files

-   To create a configuration for Logback, you can use XML as well as Groovy.
-   There are three valid standard file names:
1.  *logback-test.xml*
2.  *logback.groovy*
3.  *logback.xml*

**Let’s see what a basic configuration equivalent to the default one looks like:**

\<configuration\>

\<appender name="STDOUT" class="ch.qos.logback.core.ConsoleAppender"\>

\<encoder\>

\<pattern\>%d{HH:mm:ss.SSS} [%thread] %-5level %logger{50} - %msg%n\</pattern\>

\</encoder\>

\</appender\>

\<root level="debug"\>

\<appender-ref ref="STDOUT" /\>

\</root\>

\</configuration\>

-   This configuration defines a *ConsoleAppender* with a *PatternLayout*. Log messages on the console will be displayed at level DEBUG or below, using the defined pattern:
-   18:00:30.143 [main] DEBUG com.stackify.services.UserServiceTest - UserService Test.

## 6. Logback Components

Three main components of Logback

1.  Appenderss
2.  Layout
3.  Loggers

## 6.1 Appenders

-   In the Logback, **appenders are the elements responsible for writing log statements**.
-   All appenders must implement the *Appender* interface.
-   Furthermore, each appender corresponds to a certain type of output or mode of sending data.
-   Here are some of the most helpful appenders:
1.  *ConsoleAppender* – writes messages to the system console
2.  *FileAppender* – appends messages to a file
3.  *RollingFileAppender* – extends the *FileAppender* with the ability to roll over log files
4.  *SMTPAppender* – sends log messages in an email, by default only for ERROR messages
5.  *DBAppender* – adds log events to a database
6.  *SiftingAppender* – separates logs based on a runtime attribute

## *6.1.1 The Console Appender*

-   The *ConsoleAppender* is one of the more basic appenders available in Logback, as it can only log messages to *System.out* or *System.err*.
-   By default, messages are logged to the *System.out*, but you can change that using the *target* attribute:

\<appender name="STDOUT" class="ch.qos.logback.core.ConsoleAppender"\>

...

\<target\>System.err\</target\>

\</appender\>

## 6.1.2 The Rolling File Appender

-   Logging to file is naturally the way to go in any kind of production scenario where you need persistent logs. However, if all the logs are kept in a single file, this runs the risk of becoming too large and difficult to wade through. It’s also to make the long-term storage/warehousing of log data very difficult.That’s when rolling files come in handy.
-   To address this well-known limitation, Logback provides the **RollingFileAppender,** which rolls over the log file when certain conditions are met.
-   The appender has two components:
1.  **RollingPolicy** – which determines how the rollover is performed
2.  **TrigerringPolicy** – which determines when the file is rolled over
-   **To better understand these policies, let’s create an appender which makes use of a TimeBasedRollingPolicy and a SizeTriggeringPolicy:**

\<appender name="rollingFile" class="ch.qos.logback.core.rolling.RollingFileAppender"\>

\<rollingPolicy class="ch.qos.logback.core.rolling.TimeBasedRollingPolicy"\>

\<fileNamePattern\>log-%d{yyyy-MM-dd}.log\</fileNamePattern\>

\<maxHistory\>30\</maxHistory\>

\<totalSizeCap\>3GB\</totalSizeCap\>

\</rollingPolicy\>

\<triggeringPolicy class="ch.qos.logback.core.rolling.SizeBasedTriggeringPolicy"\>

\<maxFileSize\>3MB\</maxFileSize\>

\</triggeringPolicy\>

\<encoder\>

-   \<pattern\>[%thread] %-5level %logger{36} - %msg%n\</pattern\>
-   \</encoder\>

\</appender\>

-   The **TimeBasedRollingPolicy** implements both a **RollingPolicy** and a **TriggeringPolicy.**
-   The example above configures the **fileNamePattern** attribute **based on the day** – which means the name of each file contains the current date, and also that the rollover will happen daily.
-   Notice how we’re limiting the log data here – **maxHistory** is set to a value of 30, alongside a **totalSizeCap** of 3GB – which means that the archived logs will be kept for the past 30 days, up to a maximum size of 3GB.
-   Finally, the **SizeBasedTriggeringPolicy** defined configures the rollover of the file whenever it reaches 3 MB. Of course that’s quite a low limit, and a mature log-viewing tool can certainly handle a lot more than that.
-   You can now see how we’ve slowly moved out from basic examples to a more realistic configuration you can actually start using as the project moves towards production.

### 6.2 Layouts

-   **The components responsible for transforming a log message to the desired output format are layouts and encoders.**
-   Some of the most commonly used layouts are *PatternLayout*, *HTMLLayout* and *XMLLayout*
-   To know more information about layouts [clickhere](https://stackify.com/logging-logback/).

### 6.3 Loggers

-   **Loggers are the third main component of Logback, which developers can use to log messages at a certain level.**
-   The library defines **5 log levels**: **TRACE, DEBUG, INFO, WARN, ERROR;** each of these has a corresponding logging method: **trace(), debug(), info(), warn(), error().**

**Example**

\<root level="debug"\>

\<appender-ref ref="STDOUT" /\>

\</root\>

Let’s now define another logger, with an INFO level, which uses the *rollingFileAppender*:

\<logger level="info" name="rollingFileLogger"\>

\<appender-ref ref="rollingFileAppender" /\>

\</logger\>

-   If you don’t explicitly define a log level, the logger will inherit the level of its closest ancestor; in this case, the DEBUG level of the root logger.

### 7. References

1.  https://stackify.com/logging-logback/
