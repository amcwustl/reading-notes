# Class 3 Reading Notes

These readings cover primitives and their object wrapper classes in Java, Exceptions, and Scan.  These readings will allow us to choose between primitives and wrapper objects based on the needs of our program, to handle exceptions thrown by our code, and to use scan to analyze input text.

## Primitives vs Objects

- Explain the difference between an “int” and an “Integer” in Java.  

> int is a primitive type whereas Integer is a reference type wrapper class.  ints take up less space but it is a primitive and not an object so it can't do some of the things that Integer can do (such as hold a null value or be used in an ArrayList).

- What is the default value for ints? Integers?

> The default value for int is 0.  For Integer the default value is "null"

- What is autoboxing? Unboxing?

> Autoboxing is the conversion of primitive types into their corresponding wrapper classes.  Unboxing is the conversion of a wrapper class into its corresponding primitive type.

## Exceptions in Java

- List the three basic categories of exceptions.

> Checked exception, error exception, runtime exception.

- What type of statement can you use to handle an exception?

> You can use a try-catch statement to handle exceptions.

## Using Scanner to Read in a file in Java

- Describe a situation where you think it would be useful to have a program that scans text.

> A program that analyzes the reading level of text.  It would be useful to break down the input to be able to pull data on the average length and complexity of words used in the text.

- What is input from a Scanner broken down into?

> It is broken down into tokens and translates individual tokens according to their data type.

## Things I Want To Know More About

- How does the compilor enforce checked exceptions?