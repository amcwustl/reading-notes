# Class 3 Readings

These readings cover lists and keys within react, the use of the spread operator on arrays, and how to pass methods from a parent to a child component in React.  These tools allow us to build more functionality into our React apps.

## React Docs - Lists and Keys

- What does .map() return?

> .map() returns a new array of the same length as the input array that has the same operation performed to ech element.

- If I want to loop through an array and display
 each value in JSX, how do I do that in React?

 > You would use .map() on the input array and return an html element for each index.

- Each list item needs a unique ____.

> Key

- What is the purpose of a key?

> Keys allow React to identify which items have changed, are added, or removed.  It should be a string that uniquely identifies a list item among its siblings.

## The Spread Operator

- What is the spread operator?

> The spread operator spreads an array into separate arguments.

- List 4 things that the spread operator can do.

> The spread operator can copy an array, combine arrays, allow us to use arrays as arguments, or add to state in React.

- Give an example of using the spread operator to combine two arrays.

> const myArray = [`🤪`,`🐻`,`🎌`]  
const yourArray = [`🙂`,`🤗`,`🤩`]  
const ourArray = [...myArray,...yourArray]  
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩

- Give an example of using the spread operator to add a new item to an array.

> const fewFruit = ['🍏','🍊','🍌']  
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]  
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]

- Give an example of using the spread operator to combine two objects into one.

> const objectOne = {hello: "🤪"}  
const objectTwo = {world: "🐻"}  
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}  
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }  
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂

## How to Pass Functions Between Components

- In the video, what is the first step that the developer does to pass functions between components?

> The first step is creating a function wherever the state is that is going to change.

- In your own words, what does the increment function do?

> increment passes in a name based on the click, and then updates the state people object by incrementing the count of the matching name by one.  This returns a new people state that gets returned to the component state.

- How can you pass a method from a parent component into a child component?

> you can pass this.method down to the person object as a prop.

- How does the child component invoke a method that was passed to it from a parent component?

> you call this.props.method()

## Things I want to know more about

- Why do list items need unique keys?