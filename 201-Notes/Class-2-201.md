# Basics of HTML, CSS, and JS

These readings are further explanation of the fundamentals of HTML, CSS, and JavaScript.  These links provide more basic information about how to structure HTML pages, how to style with CSS, and how to add dynamism to sites through the use of JS functions.

## Introduction to HTML

- Why is it important to use semantic elements in our HTML?

> It is important to use semantic elements in our HTML so the page performs well in search engine optimization, can be utilized by a screen reader, and so relevant content can be found easily by users so they don't get frustrated.  Additionally it makes it easier to apply CSS styling as we will often want to apply the same styling to elements of a similar type.

- How many levels of headings are there in HTML?

> There are 6 levels of headings in HTML.

- What are some uses for the \<sup> and \<sub> elements?

> Some possible uses for \<sup> and \<sub> are marking up items like dates, chemical formulas, and math equations.

- When using the \<abbr> element, what attribute must be added to provide the full expansion of the term?

> When using abbr element, we need to provide the title attribute to give the full expansion of the term.

## Learn CSS

- What are ways we can apply CSS to our HTML?

> We can apply CSS using an external stylesheet, an internal stylesheet, or with inline styles

- Why should we avoid using inline styles?

> We should avoid inline styles because it makes the HTML less readable and it can cause a simple change to be needed to be made in multiple places on the page to maintain consistent styling.  Generally it is poor practice to use inline styles.

- Review the block of code below and answer the following questions:
   1. What is representing the selector?

      > h2 represents the selector

   2. Which components are the CSS declarations?

      > When a property is paired with a value it is a declaration.  The pairs are color: black; and padding: 5px;

   3. Which components are considered properties?

      > Color and padding are the properties in this example.

## Javascript Basics

- What data type is a sequence of text enclosed in single quote marks?

> Strings are the datatype enclosed in single quote marks.

- List 4 types of JavaScript operators.

> Addition, assignment, strict equality, and not/does-not equal.

- Describe a real world problem you could solve with a function.

> We could use a function to check a users log in credentials and only display certain content if the user has passed a log in test.

## Making Decisions in Your Code - Conditionals

- An if statement checks a \__ and if it evaluates to __, then the code block will execute.

> An if statement checks a condition and if it evaluates to true, then the code block will execute.

- What is the use of an `else if` ?

> else if chains extra choices onto an if statement.  It evaluates if the previous if or else if statement evaluated to false.  If the else if condition evaluates to true, then the code block will execute.

- List 3 different types of comparison operators.

> === (strictly equal), < (less than), >= (greater than or equal to).

- What is the difference between the logical operator `&&` and `||`?

> && represents "AND" and allows an evaluation where multiple conditions have to be true for the whole statement to evaluate as true. || represents "OR" and will evaluate to true if either condition is true.

## Things I want to know more about

- It seems like divs and spans are used more frequently in practice than is recommended. Is this just poor design or are there other reasons to use non semantic elements?
- How common are shorthands in CSS in practice?  Do we just memorize these through practice?

## Reading Links

- [HTML Text Fundamentals](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)
- [HTML Advanced Text Formatting](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting)
- [How CSS is Structured](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_is_structured)
- [JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
- [Making Decisions - Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)
