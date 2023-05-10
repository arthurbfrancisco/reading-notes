# Reading 03: React(Passing Functions as Props)

## React Docs - lists and keys

1. The .map() function in JavaScript returns a new array that contains the results of applying a provided function on every element in the calling array. In the context of React, it's often used to create a new array of JSX elements.

2. To loop through an array and display each value in JSX in React, you can use the .map() function.

3. Each list item needs a unique key.

4. The purpose of a key in React is to help identify which items have changed, been added, or been removed. It's essential for efficient re-rendering by the React diffing algorithm.

### The Spread Operator

The spread operator (...) is a feature of modern JavaScript (ES6) that allows an iterable like an array or string to be expanded in places where zero or more arguments or elements are expected, or an object to be expanded in places where zero or more key-value pairs are expected.

### Four things the spread operator can do:

1. Copy an array
2. Concatenate or combine arrays
3. Use Math functions
4. Combine objects or add new properties to an object

Generally, the first step to pass functions between components is to define the function in the parent component.

An increment function typically increases a certain value by a specified amount, usually by 1.

You can pass a method from a parent component into a child component via props. 

The child component can invoke a method passed to it from a parent component by accessing it via props