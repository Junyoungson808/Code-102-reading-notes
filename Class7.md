# Class 7: Functions

Define a Function: 

function myFunction(p1,p2) {
    return p1 * p2;             
}

function name(parameter1, parameter2, parameter3) {
  // code to be executed
}

function toCelcius(fahrenhiet) {
    return (5/9) * (fahrenheit-32);
}
document.getElementById("demo").innerHTML = toCelcius(77);

Definitions:
A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

Function Return
When JavaScript reaches a return statement, the function will stop executing.

If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.

Functions often compute a return value. The return value is "returned" back to the "caller":

