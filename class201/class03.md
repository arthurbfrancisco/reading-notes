# 201-Class:03
## Learn:HTML

### ul-ol-li

* Use an unordered list when you have a list of items that do not have a specific order or sequence. For example, a list of ingredients for a recipe or a list of bullet points in a presentation.

* You can change the bullet style of unordered list items using CSS. The list-style-type property can be used to change the appearance of the bullets. For example, to change the bullets to squares, you can use the following CSS rule.

* Use an ordered list when you have a list of items that have a specific order or sequence. For example, a list of steps in a process or a list of numbered items in a set of instructions.

* You can use the start attribute to specify the starting number for the list. For example: 

<ol start="5"
  <li>Item 5</li>
  <li>Item 6</li>
  <li>Item 7</li>

* You can use CSS to change the appearance of the numbers or add custom content before or after the numbers:
CSS-
ol {
  counter-reset: my-counter;
}
li::before {
  counter-increment: my-counter;
  content: counter(my-counter) ") ";

An example, a custom counter called **"my-counter"** is defined using the counter-reset property. The li::before pseudo-element is then used to add the counter value and a closing parenthesis before each list item. This will result in a list that looks like "1) Item 1, 2) Item 2, 3) Item 3", and so on.
}

### "The Box Model": (padding and margin)

Margin and padding can be compared to two siblings with different personalities. Margin is the cautious introvert, always wanting space and keeping a safe distance from other elements. Padding, on the other hand, is the sociable extrovert, creating harmony by providing space between the content and the border.

In "The Box Model," margin and padding play a crucial role in setting and compromising their space. They synchronize their strengths and weaknesses to create a visually appealing and comfortable environment for the content inside the box. While margin maintains a safe distance from other elements, padding creates a cozy and welcoming space for the content. Together, they create a balance between negative space and content, making the design both functional and visually appealing.

### The four parts of an HTML element's box, as referred to by the box model, are:

1. Content: This is the actual content of the element, such as text, images, or videos.

2. Padding: This is the space between the content and the border. Padding can be adjusted using the padding property in CSS.

3. Border: This is the border that surrounds the content and padding. Borders can be customized using the border property in CSS.

4. Margin: This is the space between the border and the neighboring elements. Margins can be adjusted using the margin property in CSS.

#### Array

* JavaScript can store a variety of data types inside an array: including numbers, strings, booleans, objects, and even other arrays

* Access the values stored?

**use this to check: Array.isArray()method or arrayName[index]**

#### Shorthand operator

1. += to add 
2. -= to subtract
3. *= to multiply
4. /= to divide
5. %= to divide and remainder 
**ex:** 
let num = 10;
num %= 3; // equivalent to num = num % 3;
console.log(num); // Output: 1

 #### What is the output?
 
 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;

 This will concatenate since the boolean will be treated as a string and the result will be:
 **10dogfalse**

 ##### Real world use for Conditional statements:

Password:
 let username = 'Art';
let password = 'dontknow';

// Get user input
let inputUsername = prompt('Enter your username:');
let inputPassword = prompt('Enter your password:');

// Check answer
if (inputUsername === username && inputPassword === password) {
  alert('Login successful!');
  // access to website
} else {
  alert('Invalid username or password. Please try again.');
  // prompt user to "try again" or "reset" their password
}

**This ex; "if" statement checks whether the user-entered username and password match the hardcoded values of username and password. If the values match, the user is alerted that their login was successful and granted access to the protected parts of the website. If the values do not match, the user is alerted that their credentials are incorrect and prompted to try again**

#### Loops

ex

let numbers = [2, 5, 7, 8, 10];
let sum = 0;

// Iterate over each number in the array and add it to the sum
for (let i = 0; i < numbers.length; i++) {
  sum += numbers[i];
}

// Output the final sum
console.log(sum); // Output: 32

**This "array" of numbers is calculated to get the sum of all the numbers in the array. Using a "for" loop in JavaScript to iterate over each number in the array and adding it to the total**
















