
Hoisting
Hoisting is a mechanism where variable and function declarations are moved to the top of their scope before code execution. This means that functions and variables can be used before they are declared.

eg.1 foo() 
function foo(){ 
    console.log("Hello World"); 
    }

console.log(x); 
var x= 5;

//In this case it will throw an error because the variable declaration will only move to the top of their scope but not the value.

y= 5; console.log(y); 
var y ;

//In this case since the variable is moved to the top and we are also assigning the value of the variable before the console log statement that's why it will not throw an error and the value of y 5 will be printed.

eg.2 weekend()

var weekend = function(){ 
    console.log("Weekends classes are boring"); 
    }

//In this case also only the variable will be moved to the top but not the function because it is assigned to a variable. the functions which are declared individually to by using function keyword but not assigned to a variable will only be moved to top.

When you use let instead of var in the for loop for the above example, it creates a new binding for i in each iteration of the loop. This means that each iteration of the loop will have its own separate i variable, preserving the value of i at each iteration when the setTimeout callback is executed.

what is hoisting? 
Hoisting is a JavaScript mechanism where variable and function declarations are moved to the top of their scope before code execution. This means that functions and variables can be used before they are declared.

y= 5; 
console.log(y); 
var y ;


In javascript, we can create variable using let, var, and const. 
eg. let a = 10; eg. var isUser = true; eg. const str = "Hello";

variable created using var are both function and global scoped.This means that they are accessible within the entire function in which they are defined, or globally if they are defined outside of a function.

let and const are block scoped, This means that they are only accessible within the block (a pair of curly braces) in which they are defined. also const variables cannot be changed once they have been assigned a value.

eg. 1 var a = 10;

function foo(){ 
    console.log("a in foo",a); 
    var b = 20; 
    }

foo() 
console.log("b outside foo",b);

//In the above example it will throw error while console logging the value of b because it is declared within the function and will not be accessible outside of the function.
