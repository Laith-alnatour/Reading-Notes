# Passing Functions as Props


**Here very important base of React**


> Reading

### React Docs - lists and keys

1. **What does .map() return?**

Return Value: It returns a new array and elements of arrays are result of callback function

2. **If I want to loop through an array and display each value in JSX, how do I do that in React?**

{
  todos.map((todo) => (
    <p key={todo.id}>
      {todo.text} - {todo.status}
    </p>
  ));
}


3. **Each list item needs a unique _Among Siblings___.**


4. **What is the purpose of a key?**

Keys help React identify which items have changed, are added, or are removed

### The Spread Operator

1. **What is the spread operator?**

refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments.

2. **List 4 things that the spread operator can do.**

. find the largest number in an array
. Copying an array
. Concatenating or combining arrays
. Using Math functions

3. **Give an example of using the spread operator to combine two arrays.**

const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩


4. **Give an example of using the spread operator to add a new item to an array.**

const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]


5. **Give an example of using the spread operator to combine two objects into one.**

const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂


> ## Videos

1. **In the video, what is the first step that the developer does to pass functions between components?**


2. **In your own words, what does the increment function do?**


3. **How can you pass a method from a parent component into a child component?**


4. **How does the child component invoke a method that was passed to it from a parent component?**


> Bookmark and Review

. [React Tutorial through ‘Declaring a Winner’](https://reactjs.org/tutorial/tutorial.html)

. [React Docs - Lifting State Up](https://reactjs.org/docs/lifting-state-up.html)


## Things I want to know more about

Nothing for today

