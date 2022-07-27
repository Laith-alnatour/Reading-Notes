# Putting it all together


**Below you will find some reading material, code samples, and some additional resources that support today’s topic and the upcoming lecture.**

**Review the Submission Instructions for guidance on completing and submitting this assignment.**


> Reading

### React Docs - Thinking in React

1. **What is the single responsibility principle and how does it apply to components?**


The single-responsibility principle (SRP) is a computer-programming principle that states that every module, class or function in a computer program should have responsibility over a single part of that program's functionality, and it should encapsulate that part.


2. **What does it mean to build a ‘static’ version of your application?**

Static applications and websites render in the user's browser without the need for server side processing, this means that all the rendering of HTML, CSS, and JavaScript is done on the client side, rather then relying on server side technologies.

3. **Once you have a static application, what do you need to add?**

To build a static version of your app that renders your data model, you’ll want to build components that reuse other components and pass data using props. props are a way of passing data from parent to child.

4. **What are the three questions you can ask to determine if something is state?**


a.Is it passed in from a parent via props? If so, it probably isn’t state.

b.Does it remain unchanged over time? If so, it probably isn’t state.

c.Can you compute it based on any other state or props in your component? If so, it isn’t state.


5. **How can you identify where state needs to live?**

Identify every component that renders something based on that state.

. Find a common owner component (a single component above all the components that need the state in the hierarchy).

. Either the common owner or another component higher up in the hierarchy should own the state.

. If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

### Higher-Order Functions

1. **What is a “higher-order function”?**

A large program is a costly program, and not just because of the time it takes to build. Size almost always involves complexity, and complexity confuses programmers. Confused programmers, in turn, introduce mistakes (bugs) into programs. A large program then provides a lot of space for these bugs to hide, making them hard to find.

2. **Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?**

 logical operator that helps compare two data cells of the same data type. It is denoted by the symbol “>=” and returns the following values: “True,” if the first value is either greater than or equal to the second value

3. **Explain how either map or reduce operates, with regards to higher-order functions.**

Map operates on a list of values in order to produce a new list of values, by applying the same computation to each value. Reduce operates on a list of values to collapse or combine those values into a single value (or some number of values), again by applying the same computation to each value.


> Bookmark and Review

. [React Docs - Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

. [Higher-Order Functions](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

## Things I want to know more about

Nothing for today
