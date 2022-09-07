## JS Scope

**Content**

**1. JS Scope**

1.1 Block Scope

1.2 Local Scope

1.3 Function Scope

1.4 Global JS Variables

1.4.1 Global Scope

1.4.2 Automatically Global

1.5 The Lifetime of JS Variables

1.6 Function Arguments

**2. References**

## 1. JS Scope

-   Scope determines the accessibility of variables, objects, and functions from different parts of the code.
-   JavaScript has 3 types of scope:
1.  Block scope
2.  Function scope
3.  Global scope

## 1.1 Block Scope

-   Before ES6 (2015), JavaScript had only **Global Scope** and **Function Scope**.
-   ES6 introduced two important new JavaScript keywords: let and const.
-   These two keywords provide **Block Scope** in JavaScript.
-   Variables declared inside a { } block cannot be accessed from outside the block:

**Example-1**

{  
let x = 2;  
}  
// x can NOT be used here

-   Variables declared with the var keyword can NOT have block scope.
-   Variables declared inside a { } block can be accessed from outside the block.

**Example-2**

{  
var x = 2;  
}  
// x CAN be used here

## 1.2 Local Scope

-   Variables declared within a JavaScript function, become **LOCAL** to the function.
-   Local variables have **Function Scope**:
-   They can only be accessed from within the function.
-   Since local variables are only recognized inside their functions, variables with the same name can be used in different functions.
-   Local variables are created when a function starts, and deleted when the function is completed.

**Example**

// code here can NOT use carName

function myFunction()

{  
let carName = "Volvo";  
// code here CAN use carName  
}

// code here can NOT use carName

## 1.3 Function Scope

-   JavaScript has function scope: Each function creates a new scope.
-   Variables defined inside a function are not accessible (visible) from outside the function.
-   Variables declared with var, let and const are quite similar when declared inside a function.
-   They all have **Function Scope**:

**Example**

function myFunction()

{  
var carName = "Volvo"; // Function Scope  
}

function myFunction()

{  
let carName = "Volvo"; // Function Scope  
}

function myFunction()

{  
const carName = "Volvo"; // Function Scope  
}

## 1.4 Global JS Variables

-   A variable declared outside a function, becomes **GLOBAL**.
-   A global variable has **Global Scope**:
-   All scripts and functions on a web page can access it.

**Example**

let carName = "Volvo";  
// code here can use carName

function myFunction()

{  
// code here can also use carName  
}

## 1.4.1 Global Scope

-   Variables declared **Globally** (outside any function) have **Global Scope**.
-   **Global** variables can be accessed from anywhere in a JavaScript program.
-   Variables declared with var, let and const are quite similar when declared outside a block.
-   They all have **Global Scope**:

**Example**

var x = 2; // Global scope

let x = 2; // Global scope

const x = 2; // Global scope

## 1.4.2 Automatically Global

-   If you assign a value to a variable that has not been declared, it will automatically become a **GLOBAL** variable.

**Example**

myFunction();

// code here can use carName

function myFunction()

{  
carName = "Volvo";  
}

## Warning

-   Do NOT create global variables unless you intend to.
-   Your global variables (or functions) can overwrite window variables (or functions).  
    Any function, including the window object, can overwrite your global variables and functions.

## 1.5 The Lifetime of JS Variables

-   The lifetime of a JavaScript variable starts when it is declared.
-   Function (local) variables are deleted when the function is completed.
-   In a web browser, global variables are deleted when you close the browser window (or tab).

## 1.6 Function Arguments

-   Function arguments (parameters) work as local variables inside functions.

## 2. References

1\. https://www.w3schools.com/js/js_scope.asp
