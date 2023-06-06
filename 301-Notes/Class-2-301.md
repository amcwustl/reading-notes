# Class 2 Reading Notes

These notes cover the basic React lifecycle as well as the primary differences between state and props in React.  This is important for helping to understand the foundations of how to build a React application.

## React Lifecycle

- Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

> Based off of the diagram, the render happens before componentDidMount.

- What is the very first thing to happen in the lifecycle of React?

> The mounting phase is the first thing to happen in the lifecycle of React.

- Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

> - Constructor
> - Render
> - componentDidMount
> - React Updates
> - componentWillUnmount

- What does componentDidMount do?

> This is a method invoked immediately after a component is mounted. It can perform tasks that require access to the DOM or interactions with external API's

## React State vs Props

- What types of things can you pass in the props?

> Props are like arguments to a function.  When we want to render a component, we will pass the data we want to initialize the component to.

- What is the big difference between props and state?

> State is inside of a component while props are passed into a component.  State is for things that happen inside of a component while anything that is passed in from a parent should be a prop.

- When do we re-render our application?

> When state changes inside of an application, it will re-render.

- What are some examples of things that we could store in state?

> We could store a counter of how many times a user has done something.  We could also store some kind of user input like checkboxes or dropdowns.

## Things I want to know more about

- Do parents of children components ever know anything about the state of children elements?
