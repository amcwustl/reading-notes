# Class 03 Reading Notes

This reading is more foundational knowledge on the basics of html and css.  Additionally, it introduces loops and conditionals within Javascript which are very useful in writing dynamic code.

## Ordered and Unordered Lists

- When should you use an unordered list in your HTLM doc?

> You should use an unordered list when the order of the list items is not important.  This is typically represented as a bulleted list.

- How do you change the bullet style of unordered list items?

> You can change the bullet style of unordered list items by changing the `type` attribute.

- When should you use an ordered list vs an unordered list in HTML?

> You should use an ordered list to represent lists that would normally be preceded by a sequential marker. Unordered lists are best for things where the order doesn't matter.

- Describe two ways you can change the numbers on list items provided by an ordered list?

> You could change the type attribute to change the type of numbering (numerical, letters, roman numerals etc). You could also change the start attribute to have the list start at a specific value as opposed to 1 or a.

## The Box Model

- Describe the CSS properties of margin and padding as characters in a story.  What is their role in a story titled: "The Box Model"?

> - If the content is the VIP area of a night club, the padding is the security guards who keep all other people (blocks) away from the roped off VIP area (content).  The border is the outer walls of the night club.  The Margin is the security outside the club which keeps people a certain distance from the walls.

- List and describe the four parts of an HTML elements box as referred to by the box model.

> - Content box: This is where the content is displayed and it is in the center of the box model.
> - Padding: The next layer out.  It is the white space around the content.
> - Border: The border box wraps the content and the padding.
> - Margin: The outermost layer that goes around the other three parts.

## Arrays, Operators and Expressions, Conditionals, Loops

- What data types can you store in an array?

> We can store strings, numbers, objects, and other arrays.  Data types can be mixed in side of an array as well.

- Is the people array a valid JS array?  If so, how can i access the values stored? If not, why?

> Yes, people is a valid JS array.  We can access the values stored using bracket notation.  To access the values inside any of the arrays stored in people, we would use two sets of brackets.  Each value is indexed in its array starting with 0.

- List five shorthand operators for assignment in JS and describe what they do.

> x += f(): This would assign x = x + f() <br>
> x ^= f(): This would assign x = x ^ f() <br>
> x <<= f(): This would assign x = x << f() <br>
> x &= f(): This would assign x = x & f() <br>
> x *= f(): This would assign x = x * f()


- Read the code below and evaluate the last expression and explain what the result would be and why: <br>
`let a = 10;
let b= 'dog';
let c = false; (a+c) + b`

> This would evaluate to '10dog'.  First we would add a + c which evaluates to 10 because false is converted to 0.  Next we would concatenate the result to b because b is a string and arrive at 10dog.

- Describe a real world example of when a conditional statement should be used in a JavaScript program.

> If we want to display the temperature outside based off of a users location selection, we could use a conditional statement of if else ifs to provide output based off of their input selection.

- Give an example of when a loop is useful in Javascript.

> If we prompt the user to provide us with a number and they provide us with a non number character, we could use a while loop to continue prompting the user until the input provided is a number input.

## Things I want to know more about

- What do the bitwise assignment operators do in practice?