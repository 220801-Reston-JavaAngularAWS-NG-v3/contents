## JS Data Types

**Contents**

**1. The Concept of Data Types**

1.1 JS Types are Dynamic

1.2 JS Strings

1.3 JS Numbers

1.4 JS Booleans

1.5 The typeof Operator

1.6 Undefined

1.7 Empty Values

**2. References**

## 1. The Concept of Data Types

-   JavaScript variables can hold different data types: numbers, strings, objects and more:
-   In programming, data types is an important concept.
-   To be able to operate on variables, it is important to know something about the type.
-   Without data types, a computer cannot safely solve this:
-   When adding a number and a string, JavaScript will treat the number as a string.

## 1.1 JS Types are Dynamic

-   JavaScript has dynamic types. This means that the same variable can be used to hold different data types:

**Example**

![](media/afa69131c5926be76545ffee21d029f7.png)

## 1.2 JS Strings

-   A string (or a text string) is a series of characters like "John Doe".
-   Strings are written with quotes. You can use single or double quotes:

**Example-1**

![](media/e7cbff0b30169ee38c74fa5d0f4ac72a.png)

-   You can use quotes inside a string, as long as they don't match the quotes surrounding the string:

**Example-2**

let answer1 = "It's alright"; // Single quote inside double quotes  
let answer2 = "He is called 'Johnny'"; // Single quotes inside double quotes  
let answer3 = 'He is called "Johnny"'; // Double quotes inside single quotes

## 1.3 JS Numbers

-   JavaScript has only one type of numbers.
-   Numbers can be written with, or without decimals:

**Example**

![](media/f0c15d7d838fe35097f752bf22b7cf80.png)

-   Extra large or extra small numbers can be written with scientific (exponential) notation:

**Example-2**

let y = 123e5; // 12300000  
let z = 123e-5; // 0.00123

## 1.4 JS Booleans

-   Booleans can only have two values: true or false.
-   Booleans are often used in conditional testing.

**Example**

![](media/aee1de752a1538392815e5c9ba9cda7d.png)

## 1.5 The typeof Operator

-   You can use the JavaScript typeof operator to find the type of a JavaScript variable.
-   The typeof operator returns the type of a variable or an expression:

**Example**

![](media/2e0aba2f3af4a5332705745191be45ae.png)

## 1.6 Undefined

-   In JavaScript, a variable without a value, has the value undefined. The type is also undefined.

**Example-1**

![](media/63e9389d7030aa8adeb7f6d3ec08d674.png)

-   Any variable can be emptied, by setting the value to undefined. The type will also be undefined.

**Example-2**

![](media/72586f739208144be7fb92110cacc041.png)

## 1.7 Empty Values

-   An empty value has nothing to do with undefined.
-   An empty string has both a legal value and a type.

**Example**

![](media/8cc1ccac827e648722873b16942c10c3.png)

## 2. References

1\. https://www.w3schools.com/js/js_datatypes.asp
