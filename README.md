# se2202_tutorial3

## Task 1: Callback functions - Sending functions as arguments to other functions

Let's say we have two bindings to two numbers and a function that takes two parameters

let x=5, y=6;
let  add = function(a,b) {
       return a + b;
};

When we pass those bindings as arguments to the function as shown in the following statement:

let z = add(x,y);

The parameters of the function would form new bindings to the same values, i.e., inside the function, a will refer to the same value that x refers to, which is 5, and b would refer to the same value of y, which is 6.

Since functions are also values, we can pass them as arguments just like we did with the numbers.
The goal of this task is to exercise this concept. The file callbackFunctions.js has the starter code for this task; update the code according to the comments there.

