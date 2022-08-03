# In memory storage


**Below you will find some reading material, code samples, and some additional resources that support today’s topic and the upcoming lecture.**



> Reading

### Understanding the JavaScript Call Stack

1. **What is a ‘call’?**

function invocation


2. **How many ‘calls’ can happen at once?**

1 in synchronous programming


3. **What does LIFO mean?**

Last In First Out


4. **Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.**


function firstFunction(){

  throw new Error('Stack Trace Error');
  
}

function secondFunction(){

firstFunction();

}


function thirdFunction(){

secondFunction();

}

thirdFunction();

5. **What causes a Stack Overflow?**

A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.


### JavaScript error messages

1. **What is a ‘reference error’?**

when try to use a variable that is not yet declared 


2. **What is a ‘syntax error’?**

this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

3. **What is a ‘range error’?**

When try to manipulate an object with some kind of length and give it an invalid length


4. **What is a ‘tyep error’?**

type error show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

5. **What is a breakpoint?**

the point where our code breaks, we will be able to see what has happened before that point 

6. **What does the word ‘debugger’ do in your code?**

will achieve a breakpoint in the line of code we want to break at.


> Bookmark and Review

. [JavaScript error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c?gi=d5bb57c1c187)

. [JavaScript errors reference on MDN](https://gist.github.com/brookr/5977550](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)


## Things I want to know more about

Nothing for today
