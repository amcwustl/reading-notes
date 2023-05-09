# Class 7 Reading Notes

This reading delves into the key principle of object oriented programming which is domain modeling, constructors, and prototypes.  These tools will make it much cleaner to create object classes and use smart code to fill them in.  Additionally, this reading covers how to create and format HTML table elements.

## Domain Modeling

- Expain why we need domain modeling.

> We need domain modeling to create a conceptual model of a specific problem.  It will describe the attributes and behaviors that our entities have in common.

## HTML Table Basics

- Why should tables not be used for page layouts?

> We should avoid tables for page layouts because it reduces accessibility for visually impaired users, it makes the code harder to write, and they are not automatically responsive.

- List and describe 3 different semantic HTML elements used in an HTML `table`.

> `td` is the element that describes a single cell of data in our table.
> `tr` is the element that encloses the first and last cell that will make up in entire row of data.  It semantically tells the HTML where each new row of the table begins and ends.
> `th` is the element for table headers.  This semantically tells HTML what should go at the top of each column.

## Introducing Constructors

- What is a constructor and what are some advantages to using it?

> A constructor gives us the shape of an object and allows us to create new objects of the same format easily many times.  This is advantageous because if we have many of the same object, we don't need to manually type out each one, we can initialize them with calls to our constuctor.

- How does the term `this` differ when used in an object literal versus when used in a constructor?

> In an object, `this` refers to the object that is inside.  When it is in a constructor, it allows us to use the same method definition for every object we create.

## Object Prototypes Using a Constructor

- Explain prototypes and inheritance via an analogy from your previous work experience.

> Prototypes reminds me of duplicate forms that I needed to fill out in a previous job.  While the details of the data entry remained the same, ultimately the format of the data and the values we needed to enter were the same.  In order to do this, we created a template table and then just populate the key values to fill it out.  Other cells were calculated excel functions which would then fill out the rest of the form automatically.  This is much like creating a function prototype.  We create the structure of how the data will be stored, and then when we create a new object, we pass some key values into it and end up with an object that follows the same format as many others that will be entered.

## Things I want to know more about

- Will we largely be using the `class` notation demonstrated in the prototype article?
