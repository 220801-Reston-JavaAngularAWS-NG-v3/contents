## JS Strict Mode

**Content**

1\. JavaScript Use Strict

1.1 The "use strict" Directive

2\. Declaring Strict Mode

3\. Why Strict Mode?

3.1 Not Allowed in Strict Mode

4\. References

## 1. JavaScript Use Strict

-   "use strict"; Defines that JavaScript code should be executed in "strict mode".

## 1.1 The "use strict" Directive

-   The "use strict" directive was new in ECMAScript version 5.
-   It is not a statement, but a literal expression, ignored by earlier versions of JavaScript.
-   The purpose of "use strict" is to indicate that the code should be executed in "strict mode".

## 2. Declaring Strict Mode

-   Strict mode is declared by adding "use strict"; to the beginning of a script or a function.
-   Declared at the beginning of a script, it has global scope (all code in the script will execute in strict mode):
-   The syntax, for declaring strict mode, was designed to be compatible with older versions of JavaScript.
-   So "use strict"; only matters to new compilers that "understand" the meaning of it.

**Syntax**: "use strict";

## 3. Why Strict Mode?

-   Strict mode makes it easier to write "secure" JavaScript.
-   Strict mode changes previously accepted "bad syntax" into real errors.
-   **Example**, in normal JavaScript, mistyping a variable name creates a new global variable. In strict mode, this will throw an error, making it impossible to accidentally create a global variable.
-   In normal JavaScript, a developer will not receive any error feedback assigning values to non-writable properties.
-   In strict mode, any assignment to a non-writable property, a getter-only property, a non-existing property, a non-existing variable, or a non-existing object, will throw an error.

## 3.1 Not Allowed in Strict Mode

**1. Using a variable, without declaring it, is not allowed:**

**Example:**

"use strict";  
x = 3.14; // This will cause an error

**2. Duplicating a parameter name is not allowed:**

**Example:**

"use strict";  
function x(p1, p1) {}; // This will cause an error

**3. Inside function, a variable, without declaring it, is not allowed:**

**Example:**

"use strict";  
myFunction();

function myFunction() {  
y = 3.14; // This will also cause an error because y is not declared  
}

**4. This keyword, is not allowed**

-   The **this** keyword in functions behaves differently in strict mode.
-   The **this** keyword refers to the object that called the function.
-   If the object is not specified, functions in strict mode will return undefined and functions in normal mode will return the global object (window):

**Example:**

"use strict";  
function myFunction() {  
alert(this); // will alert "undefined"  
}  
myFunction();

**Note**

-   The "use strict" directive is only recognized at the **beginning** of a script or a function.

## 4. References

1.https://www.w3schools.com/js/js_strict.asp
