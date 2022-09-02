## Flexbox

**Content**

**1. Flexbox**

1.1 Horizontal Direction

1.2 Vertical Direction

1.3 Justify Content

**2. References**

## 1. Flexbox

-   The biggest difference between Bootstrap 3 and Bootstrap 4 & 5 is that Bootstrap 5 now uses flexbox, instead of floats, to handle the layout.
-   To create a flexbox container and to transform direct children into flex items, use the d-flex class:

**Example**

\<div class="d-flex p-3 bg-secondary text-white"\>  
\<div class="p-2 bg-info"\>Flex item 1\</div\>  
\<div class="p-2 bg-warning"\>Flex item 2\</div\>  
\<div class="p-2 bg-primary"\>Flex item 3\</div\>  
\</div\>

**Output**

![](media/b63fc21de23928964998d3462960b7cd.png)

-   To create an inline flexbox container, use the d-inline-flex class:

**Example**

\<div class="d-inline-flex p-3 bg-secondary text-white"\>  
\<div class="p-2 bg-info"\>Flex item 1\</div\>  
\<div class="p-2 bg-warning"\>Flex item 2\</div\>  
\<div class="p-2 bg-primary"\>Flex item 3\</div\>  
\</div\>

**Output**

![](media/3c79e609d6952062a9e94569f93c0449.png)

## 1.1 Horizontal Direction

-   Use .flex-row to display the flex items horizontally (side by side). This is default.

**Tip:** Use .flex-row-reverse to right-align the horizontal direction:

**Example**

\<div class="d-flex flex-row bg-secondary"\>  
\<div class="p-2 bg-info"\>Flex item 1\</div\>  
\<div class="p-2 bg-warning"\>Flex item 2\</div\>  
\<div class="p-2 bg-primary"\>Flex item 3\</div\>  
\</div\>

\<div class="d-flex flex-row-reverse bg-secondary"\>  
\<div class="p-2 bg-info"\>Flex item 1\</div\>  
\<div class="p-2 bg-warning"\>Flex item 2\</div\>  
\<div class="p-2 bg-primary"\>Flex item 3\</div\>  
\</div\>

**Output**

![](media/3ac8221360c334ee7fe8e8b43006e7c9.png)

## 1.2 Vertical Direction

-   Use .flex-column to display the flex items vertically (on top of each other), or .flex-column-reverse to reverse the vertical direction:

**Example**

\<div class="d-flex flex-column"\>  
\<div class="p-2 bg-info"\>Flex item 1\</div\>  
\<div class="p-2 bg-warning"\>Flex item 2\</div\>  
\<div class="p-2 bg-primary"\>Flex item 3\</div\>  
\</div\>

\<div class="d-flex flex-column-reverse"\>  
\<div class="p-2 bg-info"\>Flex item 1\</div\>  
\<div class="p-2 bg-warning"\>Flex item 2\</div\>  
\<div class="p-2 bg-primary"\>Flex item 3\</div\>  
\</div\>

**Output**

![](media/7c3c16592f2f8718d3a7ebe48a48f6be.png)

## 1.3 Justify Content

-   Use the .justify-content-\* classes to change the alignment of flex items. Valid classes are start (default), end, center, between or around:

**Example**

\<div class="d-flex justify-content-start"\>...\</div\>  
\<div class="d-flex justify-content-end"\>...\</div\>  
\<div class="d-flex justify-content-center"\>...\</div\>  
\<div class="d-flex justify-content-between"\>...\</div\>  
\<div class="d-flex justify-content-around"\>...\</div\>

**Output**

![](media/6176c83fbb84d86242090dbf069fc6f1.png)

-   To know more details about flexbox [Clickhere](https://www.w3schools.com/bootstrap5/bootstrap_flex.php)

## 2. References

https://www.w3schools.com/bootstrap5/bootstrap_flex.php
