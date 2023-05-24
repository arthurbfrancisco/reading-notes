# 201-Class:02

**Apply CSS to our HTML?**
Inline CSS: h1 style="color: red;">Hello World
Internal CSS: style> h1 { color: red; } style 
External CSS: link rel="stylesheet" href="style.css">

## Inline style should be avoided! CSS

What is representing the selector?
Which components are the CSS declarations?
Which components are considered properties?

Selector: In CSS, a selector is used to target and select specific HTML elements on a web page. It determines which elements the CSS rules should be applied to. Selectors can target elements based on their tag name, class, ID, attributes, or relationship with other elements. For example, the selector ".my-class" targets all elements with the class name "my-class".

CSS Declarations: CSS declarations consist of one or more property-value pairs that define the visual appearance and behavior of the selected elements. Each declaration is enclosed within curly braces ({}) and contains a property and its corresponding value. For example, in the declaration "color: red;", "color" is the property, and "red" is its value. Multiple declarations can be grouped together within the same selector.

Properties: CSS properties are the individual visual or behavioral characteristics that you can apply to selected elements. They specify aspects such as color, size, font, margin, padding, positioning, and more. Examples of CSS properties include "color", "font-size", "margin-top", "background-image", "border-radius", etc. Each property has its own set of accepted values that determine how it affects the appearance or behavior of the targeted elements.

### Javascripts

Sequence of text enclosed in single quote marks?
Strings can also be enclosed in double quotes, and backticks (``) can be used to create template literals

List 4 types of JavaScript operators.
1.  Arithmetic operators perform mathematical operations on numeric values, such as addition (+), subtraction (-), multiplication (*), division (/), and modulo (%).

2. Comparison operators compare two values and return a Boolean value (true or false), such as equality (==), inequality (!=), strict equality (===), strict inequality (!==), greater than (>), greater than or equal to (>=), less than (<), and less than or equal to (<=

3. Logical operators perform logical operations on Boolean values, such as logical AND (&&), logical OR (||), and logical NOT (!).

4. Logical operators perform logical operations on Boolean values, such as logical AND (&&), logical OR (||), and logical NOT (!).

**Real world Problem solve with a Function.**
Can be used by the store to calculate the total cost of any order based on the quantity and price per item, and to determine if the order qualifies for a discount.
ex:
function calculateOrderCost(quantity, pricePerItem) {
  let totalCost = quantity * pricePerItem;
  if (totalCost > 100) {
    totalCost *= 0.9; // apply 10% discount
  }
  return totalCost;
}
let orderCost = calculateOrderCost(5, 25); // calculate cost for 5 items at $25 each
console.log(orderCost); // output: 125

orderCost = calculateOrderCost(10, 8); // calculate cost for 10 items at $8 each
console.log(orderCost); // output: 80

orderCost = calculateOrderCost(20, 6); // calculate cost for 20 items at $6 each
console.log(orderCost); // output: 108 (includes 10% discount for orders over $100)

### An if statement checks a **conditon** and if it evaluates to **tue**, then the code block will execute.

What is the use of an else if?
let score = 80;

if (score >= 90) {
  console.log("A");
} else if (score >= 80) {
  console.log("B");
} else if (score >= 70) {
  console.log("C");
} else {
  console.log("F");
}

#### 3 different types of comparison operators.
1. Equal to (==)
2. Strict equal to (===)
3. Not equal to (!=)
4. Strict not equal to (!==)

##### What is the difference between the logical operator && and ||?

The main difference between && and || is their behavior when evaluating multiple conditions:

&& (Logical AND): The && operator returns true if both conditions are true, and false otherwise. It evaluates the second condition only if the first condition is true, using short-circuit evaluation. If the first condition is false, then the second condition is not evaluated.

ex. if (x > 0 && y < 10) {
  // executes only if x is greater than 0 and y is less than 10
}