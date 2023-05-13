# Reading 05:Thinking in React, Higher-order functions

## What is the single responsibility principle and how does it apply to components?

The single responsibility principle (SRP) states that a component should have a single responsibility or a single reason to change. In the context of React components, it means that each component should ideally have a focused purpose and handle a specific part of the user interface or functionality. This makes the component easier to understand, test, and maintain.

## What does it mean to build a ‘static’ version of your application?

Building a 'static' version of your application means creating a version of your application that doesn't have interactivity or dynamic behavior. It typically involves rendering the user interface with static data, without any user interactions or data fetching. The goal is to establish the basic structure, layout, and visual representation of your application before adding dynamic functionality.

### Once you have a static application, what do you need to add?

Once you have a static application, you need to add interactivity and dynamic behavior. This involves incorporating features such as event handling, data fetching, user input validation, state management, and updating the UI based on changes in data or user actions. By adding these dynamic elements, you transform the static application into an interactive and functional one.

### What are the three questions you can ask to determine if something is state?

To determine if something is state, you can ask yourself the following questions:

Does it change over time?
Is it passed in from a parent component via props?
Can it be computed based on other state or props?
If the answer to any of these questions is yes, then the item is likely to be state and should be managed accordingly.

#### How can you identify where state needs to live?

Identifying where state needs to live can be done by considering the following guidelines:

Identify which components need the state data to render their part of the UI correctly.
Find the closest common ancestor component of those components.
Move the state data and the state management logic to that common ancestor component.
Pass the state data down to the child components as props, so they can access and use the data as needed.
The goal is to keep the state as high up in the component tree as possible, allowing the data to be shared and accessed by the relevant components while keeping the component hierarchy organized and manageable.

### What is a “higher-order function”?

A higher-order function is a function that takes one or more functions as arguments or returns a function as its result. In other words, it either accepts functions as parameters or produces functions as output. Higher-order functions are a fundamental concept in functional programming.

#### Explore the greaterThan function as defined in the reading. In your own words, 

Line 2 of the greaterThan function is defining and returning an anonymous function that takes a parameter m and checks if m is greater than the value n captured in the outer scope. In other words, it creates a closure that "remembers" the value of n and allows the returned function to make comparisons with any provided m value.

To break it down further:

The greaterThan function takes a parameter n.
Inside the function, it defines an anonymous function using arrow syntax: m => m > n.
This anonymous function compares the parameter m with the captured value n, checking if m is greater than n.
Finally, the greaterThan function returns this anonymous function as its result.
By calling greaterThan(10), we create a new function greaterThan10 that checks if a given value is greater than 10. When we invoke greaterThan10(11), it returns true since 11 is indeed greater than 10.

#### what is line 2 of this function doing?

Map and reduce are both higher-order functions commonly used in functional programming.

Map: The map function transforms each element of an array by applying a given function to it and returns a new array containing the transformed values. It takes an input array, applies the provided function to each element, and creates a new array with the results. For example, you can use map to double the values of an array: [1, 2, 3].map(x => x * 2) will result in [2, 4, 6].

Reduce: The reduce function takes an array and reduces it to a single value by applying a reducer function. The reducer function takes an accumulator and the current element of the array and returns the updated accumulator value. It accumulates the result of the computation performed on each element of the array. For example, you can use reduce to calculate the sum of an array: [1, 2, 3].reduce((acc, curr) => acc + curr, 0) will result in 6 (the initial value of the accumulator is 0).

#### Explain how either map or reduce operates, with regards to higher-order functions.

In both cases, map and reduce are higher-order functions because they accept other functions as arguments (the mapping function or the reducer function) and operate on arrays, transforming or aggregating data based on those functions.