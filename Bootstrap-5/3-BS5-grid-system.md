## Bootstrap 5 Grid System

**Content**

1\. Bootstrap 5 Grid System

2\. Grid Classes

3\. Basic Structure of a Bootstrap 5 Grid

4\. Three Equal Columns

5\. Responsive Columns

5.1 Two Unequal Responsive Columns

6\. References

## 1. Bootstrap 5 Grid System

-   Bootstrap's grid system is built with flexbox and allows up to 12 columns across the page.
-   If you do not want to use all 12 columns individually, you can group the columns together to create wider columns:

**Example**

![](media/62e3c9f27050b453d43690cbb7e39bc1.png)

-   The grid system is responsive, and the columns will re-arrange automatically depending on the screen size.
-   Make sure that the sum adds up to 12 or fewer (it is not required that you use all 12 available columns).

## 2. Grid Classes

The Bootstrap 5 grid system has six classes:

-   .col- (extra small devices - screen width less than 576px)
-   .col-sm- (small devices - screen width equal to or greater than 576px)
-   .col-md- (medium devices - screen width equal to or greater than 768px)
-   .col-lg- (large devices - screen width equal to or greater than 992px)
-   .col-xl- (xlarge devices - screen width equal to or greater than 1200px)
-   .col-xxl- (xxlarge devices - screen width equal to or greater than 1400px)

The classes above can be combined to create more dynamic and flexible layouts.

**Tip:** Each class scales up, so if you want to set the same widths for sm and md, you only need to specify sm.

## 3. Basic Structure of a Bootstrap 5 Grid

The following is a basic structure of a Bootstrap 5 grid:

**Example-1**

\<!-- Control the column width, and how they should appear on different devices --\>  
\<div class="row"\>  
\<div class="col-\*-\*"\>\</div\>  
\<div class="col-\*-\*"\>\</div\>  
\</div\>  
\<div class="row"\>  
\<div class="col-\*-\*"\>\</div\>  
\<div class="col-\*-\*"\>\</div\>  
\<div class="col-\*-\*"\>\</div\>  
\</div\>

**Example-2**

\<!-- Or let Bootstrap automatically handle the layout --\>  
\<div class="row"\>  
\<div class="col"\>\</div\>  
\<div class="col"\>\</div\>  
\<div class="col"\>\</div\>  
\</div\>

-   In example-1: create a row (\<div class="row"\>). Then, add the desired number of columns (tags with appropriate .col-\*-\* classes). The first star (\*) represents the responsiveness: sm, md, lg, xl or xxl, while the second star represents a number, which should add up to 12 for each row.
-   In example-2: instead of adding a number to each col, let bootstrap handle the layout, to create equal width columns: two "col" elements = 50% width to each col, while three cols = 33.33% width to each col. Four cols = 25% width, etc. You can also use .col-sm\|md\|lg\|xl\|xxl to make the columns responsive.

## 4. Three Equal Columns

![](media/4f1a273848cef8439c6dfa0578bbb543.png)

-   The following example shows how to create three equal-width columns, on all devices and screen widths:

**Example**

\<div class="row"\>  
\<div class="col"\>.col\</div\>  
\<div class="col"\>.col\</div\>  
\<div class="col"\>.col\</div\>  
\</div\>

## 5. Responsive Columns

![](media/4941482033bd4ffa58f134aa2835759a.png)

-   The following example shows how to create four equal-width columns starting at tablets and scaling to extra large desktops.
-   **On mobile phones or screens that are less than 576px wide, the columns will automatically stack on top of each other**:

**Example**

\<div class="row"\>  
\<div class="col-sm-3"\>.col-sm-3\</div\>  
\<div class="col-sm-3"\>.col-sm-3\</div\>  
\<div class="col-sm-3"\>.col-sm-3\</div\>  
\<div class="col-sm-3"\>.col-sm-3\</div\>  
\</div\>

## 5.1 Two Unequal Responsive Columns

![](media/554dfd9df586db0708f89a715fb36dd0.png)

-   The following example shows how to get two various-width columns starting at tablets and scaling to large extra desktops:

**Example**

\<div class="row"\>  
\<div class="col-sm-4"\>.col-sm-4\</div\>  
\<div class="col-sm-8"\>.col-sm-8\</div\>  
\</div\>

## 6. References

1.  https://www.w3schools.com/bootstrap5/bootstrap_grid_basic.php
