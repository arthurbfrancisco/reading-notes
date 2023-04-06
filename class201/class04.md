# 201-Class:04

## Learning: HTMl, CSS, JS

To create a basic link in HTML, we use the anchor element <a> and wrap the text or other content inside it.href attribute is used in the HTML **Anchor** element to specify the URL, href attribute would be set to href="./about.html".

## ensure the accessibility of links:

1. Use descriptive link text
2. Add title attributes
3. Use contrasting colors
4. Make links keyboard accessible
5. Use underlines or other visual cues
6. Avoid using only images for links

### CSS Layout: Normal Flow CSS Layout: Positioning

1. Default behavior of how elements are positioned and flow within the layout of a web page
2. **Float, position, and display** can be used to alter the normal flow of elements ex: example, setting the float property to left or right will cause an element to float to the left or right of its container, causing other elements to wrap around it.

The default positioning for every HTML element is called **"static positioning"**. To modify the positioning of an element, we can use CSS properties such as position, top, right, bottom, and left.

### Advantages of using absolute positioning:

1. Precise positioning: Absolute positioning allows us to position an element exactly where we want it to be on the page, with pixel-level precision. 
2. Overlapping content: Using absolute positioning
3. Flexible layout: Absolute positioning allows us to position elements in a specific location regardless of the surrounding content or layout, making it possible to create dynamic, flexible layouts.
4. Accessibility: Absolute positioning can be used to position elements off-screen, making them invisible to the user while still being accessible to assistive technology such as screen readers.
5. Animation: Absolute positioning is often used in combination with CSS animation or transitions to create dynamic, interactive effects that respond to user actions.

#### key difference between fixed positioning and absolute positioning

* The **absolute** positioning, an element is positioned relative to its nearest positioned ancestor. If there is no positioned ancestor,  it is positioned relative to the initial containing block (which is the viewport). Used for elements such as tooltips, popups or overlays that need to be positioned relative to a specific point or element in the page, but should still scroll with the rest of the page
* The **fixed** positioning, an element is positioned relative to the viewport, regardless of whether or not it has a positioned ancestor.ixed positioning is often used for elements such as navigation bars or headers that should remain visible and in the same position regardless of scrolling.

*So..element is absolutely positioned, its position is determined by its nearest positioned ancestor. But when an element is fixed positioned, its position is determined solely by its position relative to the viewport.*

### Javascripts: Functions – Reusable Blocks of Code

### Funtion vs Funtion Invocation

1. A *function* declaration is a way to define a function in JavaScript. It involves using the function keyword followed by the name of the function, a set of parentheses containing any parameters the function takes, and a set of curly braces containing the code that the function will execute when called. 

2. A *function invocation*, on the other hand, is a way to call or execute a function that has already been defined. To invoke a function, you simply write the name of the function followed by a set of parentheses containing any arguments (if the function takes any).
 *So in summary, a function declaration is a way to define a function, while a function invocation is a way to call or execute a function that has already been defined.*

 ### Parameter vs Argument
 
 A **parameter** is a variable defined in a function's declaration that represents an input value that the function expects to receive when it is called. Parameters are specified in the function's parentheses, separated by commas, and are used to define the function's behavior.

An **argument**, on the other hand, is a value that is passed to a function when it is called. Arguments are specified in the parentheses when the function is called, and are used to provide input to the function's behavior. 

*So in summary, a parameter is a variable defined in a function's declaration that represents an input value that the function expects to receive, while an argument is a value that is passed to a function when it is called, and which will be used as the input value for one or more of the function's parameters.*

#### Pair Programming:

1. Listening: hearing and interpreting the vocabulary
2. Speaking: using the correct words to communicate an idea
3. Reading: understanding what written language intends to convey
4. Writing: producing from scratch a meaningful, well structured solution

* Greater efficiency:"takes slightly longer, but produces higher-quality code that doesn’t require later effort in troubleshooting and debugging (let alone exposing users to a broken product)". Havng two brains is better than one, you often look out for each other and share knowledge and insight that drives the work to be effecient and well managed.

* Learning from fellow students: "one programmer is more experienced in a certain skill, they can teach a student who is less familiar with that area", time is valuable so having a person with knowledge to certain subject you know nothing about will speed up the process of solving the problem by having a second person watching over you.








