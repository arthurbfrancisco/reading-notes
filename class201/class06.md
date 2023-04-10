# 201-Class:06

## JavaScript Object Basics & Introduction To The DOM

### JavaScript Object Basics

1. An **object** is a way to group related information together, like a container that holds different pieces of data. It's made up of properties, which describe the data, and methods, which are actions that the object can perform. For example, you could have an object that represents a dog, with properties like name, age, and color, and methods like bark or fetch.
2. One advantage to **creating object literals** is that they are a simple and straightforward way to represent data in JavaScript. Object literals can be created quickly and easily, without needing to define a class or use constructor functions. They are also easy to read and understand, since the syntax is similar to a list of key-value pairs.
3. While **arrays** are used to store lists of values, objects are used to store collections of properties and methods. Arrays use numeric indices to access their values, while objects use string keys to access their properties. Additionally, arrays have built-in methods for manipulating their contents, while objects do not.
4. **Bracket notation** is typically used when the property name contains special characters or spaces, or when the property name is dynamic and not known until runtime. For example, if you have an object representing a person and their age is stored in a property called "date of birth", you would need to use bracket notation to access it like this: person['date of birth'].
5. The term this refers to the current instance of the dog object that is being accessed. The advantage to using this is that it allows you to refer to the specific instance of the object that is being manipulated or accessed, rather than a generic or global value. In the humanAge method, this is used to access the name and age properties of the current dog object to calculate its age in human years.
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}

### Introduction To The DOM

1. The Document Object Model (DOM) is a programming interface for web documents. It represents the web page as a structured, hierarchical tree of objects that can be manipulated with code. Each object in the tree represents an element or component of the web page, such as text, images, forms, buttons, and so on. The DOM provides a way for JavaScript to interact with and modify the content and behavior of a web page.
2. JavaScript can access and manipulate the content and behavior of a web page by interacting with the DOM. When a web page loads in a browser, the browser creates a DOM tree that represents the structure and content of the page. JavaScript can then use methods and properties of the DOM API to interact with the elements and content of the page. For example, JavaScript can add or remove elements from the page, change the text or styling of elements, respond to user events like clicks and key presses, and more. The DOM provides a way for JavaScript to access and manipulate the web page, and JavaScript provides the logic and programming to make those changes happen.

## Things I want to know more about:

How to use DOM in real world problems?
How  does JavaScript can access and manipulate the content and behavior of a web page by interacting with the DOM, how does this help my website run smooth?
Object and Object literals I never heard of, how can utilize this 
to enhance my codes or web page to run fast?
