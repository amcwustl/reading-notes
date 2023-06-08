# Class 4 Reading Notes

This reading covers React forms which will be helpful for getting user input on React pages.  The second reading covers the ternary operator which can reduce the amount of code we need to write on if else sstatements.

## React Docs - Forms

- What is a ‘Controlled Component’?

> A controlled component is a form element whose value is controlled by React state.  State is used as the single source of truth.

- Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

> With controlled components we can manage the form's state and keep it in sync with the users input.  If we want to go through validation prior to updating state, we should wait until after submit.


- How do we target what the user is entering if we have an event handler on an input field?

> We can target it using the event.target.value property.

## The conditional ternary operator explained

- Why would we use a ternary operator?

> We can use the ternary operator to accomplish a full if else statement on one line of code. This syntax performs the same task but greatly reduces how much code we need to write.

- Rewrite the following statement using a ternary statement:
 `if(x===y){
  console.log(true);
} else {
  console.log(false);
}`

> `x === y ? true : false;`

## Things I want to know more about

- What are the benefits of using controlled components in React forms compared to uncontrolled components?