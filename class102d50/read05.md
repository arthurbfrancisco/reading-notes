# Read:05-CSS(Cascading Style Sheet)

## CSS Cascading Style Sheet

* Think of a web page as a document with text and images on it. CSS is the tool that web developers use to change the way that document looks, by changing the color, font, size, and position of the text and images.

* For example, CSS can be used to change the color of text, make it bold or italicized, adjust the spacing between paragraphs, create borders around images, and much more.

* CSS works together with HTML, which is another computer language used to create web pages. HTML is used to create the structure and content of a web page, while CSS is used to style it and make it visually appealing.

* Overall, CSS is an essential tool for creating beautiful and functional websites that are easy to navigate and engaging to users.

## Three ways to insert CSS

1. **Inline CSS**: Inline CSS is when you add CSS directly to an HTML element using the style attribute. For example, you could add a style attribute to a paragraph element like this: **(style="color: red;)**. This text is red. This will make the text inside the paragraph element appear in red.

2. **Internal CSS**: Internal CSS is when you add CSS to a web page using the (style) element within the (head section) of an HTML document. For example, you could add the following code to the head section of your HTML document to style all paragraph elements to have red text: style { color: red; }...

3. **External CSS**: External CSS is when you create a separate CSS file and link it to your HTML document using the **link** element. This is the preferred method for larger projects as it allows you to keep your HTML and CSS separate, making it easier to maintain and update your code. To do this, you would create a separate file with a .css extension (e.g., styles.css) and add your CSS code to it. Then, you would link it to your HTML document like this: 
 (link rel="stylesheet" type="text/css" href="styles.css")

### Porperty of the element and how to manipulate

CSS properties are used to style and format HTML elements on a web page. They are used to control the appearance and behavior of an element, such as its size, color, position, and layout.

CSS properties consist of a name and a value, separated by a colon. For example, the color property sets the color of text, and the value can be any valid color code or color name. The font-size property sets the size of text, and the value can be specified in pixels, ems, or other units.

### Here are some examples: **Porperties**

* background-color: sets the background color of an element
* border: sets the border properties of an element, such as its width, style, and color
* padding: sets the space between the content of an element and its border
* margin: sets the space between an element and its neighboring elements
* text-align: sets the alignment of text within an element
* display: sets how an element should be displayed, such as block, inline, or inline-block
* position: sets the position of an element, such as absolute or relative

