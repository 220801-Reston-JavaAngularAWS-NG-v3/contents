# Bootstrap 5 Navbars

**Content**

**1. Navigation Bars**

1.1 Basic Navbar

**2. References**

# 1. Navigation Bars

-   A navigation bar is a navigation header that is placed at the top of the page:

![](media/72647c69480e5a1bc23c18b2877a3fd4.png)

## 1.1 Basic Navbar

-   With Bootstrap, a navigation bar can extend or collapse, depending on the screen size.
-   A standard navigation bar is created with the .navbar class, followed by a responsive collapsing class: .navbar-expand-xxl\|xl\|lg\|md\|sm (stacks the navbar vertically on xxlarge, extra large, large, medium or small screens).
-   To add links inside the navbar, use either an \<ul\> element (or a \<div\>) with class="navbar-nav". Then add \<li\> elements with a .nav-item class followed by an \<a\> element with a .nav-link class:

**Example**

\<!-- A grey horizontal navbar that becomes vertical on small screens --\>  
\<nav class="navbar navbar-expand-sm bg-light"\>

\<div class="container-fluid"\>  
\<!-- Links --\>  
\<ul class="navbar-nav"\>  
\<li class="nav-item"\>  
\<a class="nav-link" href="\#"\>Link 1\</a\>  
\</li\>  
\<li class="nav-item"\>  
\<a class="nav-link" href="\#"\>Link 2\</a\>  
\</li\>  
\<li class="nav-item"\>  
\<a class="nav-link" href="\#"\>Link 3\</a\>  
\</li\>  
\</ul\>  
\</div\>

\</nav\>

**Output**

![](media/10775947f6fd692bd6d25308d0ce63dc.png)

-   To know more information about navigation bar [clickhere](https://www.w3schools.com/bootstrap5/bootstrap_navbar.php)

# 2. References

https://www.w3schools.com/bootstrap5/bootstrap_navbar.php
