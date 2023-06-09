# Class 5 Reading Notes

This reading covers some core concepts of designing a react apps architecture.  The second reading covers higher order functions.  

## Thinking in React

- What is the single responsibility principle and how does it apply to components?

> The single responsibility principle is that a component should only do one thing.  If it does more than one thing it should be split into smaller elements.

- What does it mean to build a ‘static’ version of your application?

> Building a static version means there is no interactability.  We would not use state at all in a static version of the app.

- Once you have a static application, what do you need to add?

> Once you have a static application, you would add minimal UI to change state.  This would add some interaction.

- What are the three questions you can ask to determine if something is state?

> What components render something based on state.
> Does the state live in a common parent?
> Where should the state live?

- How can you identify where state needs to live?

> Identify the components that render something based on state.
> Find their closest common parent component.
> Decide where the state should live.

## Higher - Order Functions

- What is a “higher-order function”?

> A function that can take one or more functions as arguments and or return a function as its result.

- Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

> It defines an inner function which takes a parameter m and checks if that is greater than n.  It then returns true or false.

- Explain how either map or reduce operates, with regards to higher-order functions.

> Map transforms each element of an array based off the the function in the parentheses.  It applies the function iteratively to each element without the need of using a for loop.  It then returns a new array with the operation performed.