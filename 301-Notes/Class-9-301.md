# Class 9 Reading Notes

These readings introduce us to functional programming as well as the concepts of modules and require within node.  This is important because it will allow us to break our code up into logical segments to make it more manageable.

## Functional Programming Concepts

- What is functional programming?

> Functional Programming means building computer programs that treat computation as the evaluation of mathematical functions and doesn't change state and mutable data.

- What is a pure function and how do we know if something is a pure function?

> A pure function returns the same result if given the same arguments.  It also does not cause any ovservable side effects.

- What are the benefits of a pure function?

> Pure functions are easier to test.

- What is immutability?

> When data is immutable, its state cannot change after it is created.

- What is Referential transparency?

> If a function consistently yields the same result for the same input, it is referentially transparent.  pure functions + immutable data = referential transparency.


## Node JS Tutorial for Beginners, Modules and Require

- What is a module?

> A module is a logical bit of functionality that is seperated into another file to make management more easy.  In node, it is another JS file.

- What does the word ‘require’ do?

> require makes a module globally available in node.js.  

- How do we bring another module into the file the we are working in?

> we put require(./file name at the top of the file.)
> var counter = require('./count')

- What do we have to do to make a module available?

> We need to explicitly say what part of the file will be available outside of the module.
> module.exports = what will be available elsewhere.

## Things I want to know more about

- What do we do if a module contains multiple functions.  Do we have to export them seperately.  Do we assign them to seperate variables into the file we are importing into or are all functions available through one variable if we pass them?
