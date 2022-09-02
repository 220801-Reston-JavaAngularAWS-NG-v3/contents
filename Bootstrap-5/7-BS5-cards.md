## Bootstrap 5 Cards

**Content**

**1. Cards**

1.1 Basic Card

1.2 Header and Footer

1.3 Card Images

**2. References**

## 1. Cards

-   A card in Bootstrap 5 is a bordered box with some padding around its content.
-   It includes options for headers, footers, content, colors, etc.

![](media/b3467b9a365f863e89ddbab7034a8420.png)

## 1.1 Basic Card

-   A basic card is created with the .card class, and content inside the card has a .card-body class:

**Example**

\<div class="card"\>  
\<div class="card-body"\>Basic card\</div\>  
\</div\>

**Output**

![](media/b99596bbf3440df4683f58abb79cc4ed.png)

## 1.2 Header and Footer

-   The .card-header class adds a heading to the card and the .card-footer class adds a footer to the card:

**Example**

\<div class="card"\>  
\<div class="card-header"\>Header\</div\>  
\<div class="card-body"\>Content\</div\>  
\<div class="card-footer"\>Footer\</div\>  
\</div\>

**Output**

![](media/b2abd5dc8244a9dad899fe9807af94c6.png)

## 1.3 Card Images

![](media/b94d9d315fc00dd1ccaf9734071142ee.png)

-   Add .card-img-top or .card-img-bottom to an \<img\> to place the image at the top or at the bottom inside the card.
-   **Note** that we have added the image outside of the .card-body to span the entire width:

**Example**

\<div class="card" style="width:400px"\>  
\<img class="card-img-top" src="img_avatar1.png" alt="Card image"\>  
\<div class="card-body"\>  
\<h4 class="card-title"\>John Doe\</h4\>  
\<p class="card-text"\>Some example text.\</p\>  
\<a href="\#" class="btn btn-primary"\>See Profile\</a\>  
\</div\>  
\</div\>

For more information about cards [clickhere](https://www.w3schools.com/bootstrap5/bootstrap_cards.php)

## 2. References

1.  https://www.w3schools.com/bootstrap5/bootstrap_cards.php
