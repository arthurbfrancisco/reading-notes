# Reading 02: React(State and Props)

**Learning React is important for this module because it helps us build better user interfaces more easily and with less code. It's a useful skill for creating modern and interactive websites.**

From the article, first the 'render' happens, then 'componentDidMount' comes next. 'Render' sets up how the component looks, and 'componentDidMount' happens after the component is shown on the page.

The first thing in React's lifecycle is the 'constructor'. It happens before the component shows up on the page and sets up the starting data and functions.

## The order of events in the lifecycle is as follows:

1. constructor
2. render
3. componentDidMount
4. React Updates (when a component's props or state change)
5. componentWillUnmount
'componentDidMount' is a step in React that happens after the component appears on the page. It's used for tasks that need the component to be on the page, like getting data, setting up updates, or changing the data inside the component.

### What types of things can you pass in the props?

Props in React let you give data from a parent part to a child part. You can pass many types of data, like text, numbers, lists, and more. Props make your parts adaptable and reusable by letting them work with different data depending on what the parent part needs.

**What is the big difference between props and state?**

Props and State are both ways to manage and handle data in a React application, but they have different purposes and behaviors:

1. Props let you give data from a parent part to a child part. They can only be read, not changed, by the child part. If the data needs to change, the child should tell the parent part to update it.

2. State is for handling a part's own data. It can be changed and updated by the part. When the state changes, the part updates its appearance to show the new data. State is usually used for data that changes with time or user actions.

**Re-render our application?**

In a React app, re-rendering happens when:

The part's state gets updated with setState (for class parts) or useState (for functional parts).
The part's props change and make the part re-render.
A parent part re-renders, possibly making child parts re-render if their props or state change.
State can hold data that changes with time or user actions. Examples of data in state are:

User input like text, checkboxes, or options.
Data from an API that might change as users interact with the app or the data updates.
UI status, like if a dropdown menu or modal is open or closed.
Page info, like the current page number or total pages.
Timer or countdown state, changing over time.

**Things I want to know more about:**

Bootstrap,another type of library?
Why React is commonly used till now?
Syntax and other
How to master React in 100 days

