# Data Structures and Algorithms

These readings cover data structures and algorithms and introduce big O to determine how efficient an algorithm is.  These readings are important because it is an introduction into considering more than just solving a problem, but rather how efficient is the code we are implementing.  This is important with scaled applications as the time of operations matters when it happens frequently.

## Discussion Questions

- What is 1 of the more important things you should consider when deciding which data structure is best suited to solve a particular problem?

> When deciding on a data structure, it is important to consider the time complexity of accessing the data from within the data structure.  We should consider the methods by which we will be accessing the data and how important speed and efficiency are in finding values from within the data structure.  Additionally, it is important to consider how much space the data structure will take up especially if we have storage costs.

- How can we ensure that we’ll avoid an infinite recursive call stack?

> We can avoid an infinite recursive call stack by having a well-defined base case that acts as a terminating condition.  We should also be sure that each recursive call brings us closer to the base case.

## Things I Want To Know More About

- How important is it to consider big O complexity when the data is not especially large?
- How often is big O efficiency discussed in industry.
