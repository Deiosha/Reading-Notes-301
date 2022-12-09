### Understanding the Javascript Call Stack

1. A ‘call’ is a data structure that uses the Last In, First Out principle to temporarily store and manage function invocation.
2. One call stack can happen.
3. LIFO means last in, first out.
4. An example: 
function firstIn(){
}
Function secondIn(){
      firstIn();
}
5. stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point.

### JavaScript Error Message

1. A reference error is when you try to use a variable that is not yet declared you get this type os errors.
2. A syntax error is when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.
3. Range error is when you Try to manipulate an object with some kind of length and give it an invalid length.
4. Type error is when the type of number and strings you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.
5. A breakpoint is when javascript will stop running its code.

### Things I want to learn more about

1. I'll like to learn more about call stack. 
