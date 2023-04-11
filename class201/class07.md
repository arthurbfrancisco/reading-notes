# 201-Class:07

## Object-Oriented Programming, HTML Tables

### Domain Modeling

Domain modeling is the process of creating a conceptual model for a specific problem or subject area within a specific domain. The goal of domain modeling is to create a visual representation of the entities, relationships, and rules that govern a particular area of interest, such as a business process, software system, or scientific domain.

Domain modeling involves identifying the key entities or objects within the domain, and defining the attributes and behaviors of each entity. Relationships between entities are also defined, including any constraints or rules that govern those relationships.
 
This can be useful for a variety of purposes, such as software development, database design, and business process analysis. By creating a clear and concise representation of the key concepts and relationships within a domain, domain modeling can help stakeholders to better understand and communicate complex ideas and processes, and can also provide a foundation for more detailed design and implementation work.

### HTML Table Basics

**Tables should not be used for page layouts because they are intended for displaying tabular data, not for creating layout structures. When tables are used for layout, it can lead to several problems, including:**

1. Accessibility issues: Tables can be difficult to navigate for users with screen readers or other assistive technologies.

2. Slower page load times: Tables require more HTML and CSS code, which can slow down the loading time of a webpage.

3. Difficulties with responsiveness: Tables are not responsive by default and can be challenging to style for different screen sizes.

**Three different semantic HTML elements used in an HTML table are:**

1. <caption>: This element provides a title or caption for the table and is typically placed at the top of the table.
2. <thead>: This element is used to group the header content in a table. It typically includes <tr> and <th> elements.
3. <tbody>: This element is used to group the body content in a table. It typically includes one or more <tr> elements.

#### Introducing Constructors

Constructor is a special function that is used to create and initialize an object created with the new keyword. The constructor function typically defines properties and methods for the object.

**Advantages of using a constructor function in JavaScript include:**

* Reusability: You can create multiple objects with the same properties and methods by invoking the constructor function multiple times.
* Encapsulation: You can encapsulate object data and behavior inside the constructor function, making it easier to manage and maintain the code.
* Inheritance: You can create new objects that inherit properties and methods from a parent object.

**this**
In an object literal, the this keyword refers to the object itself.

let myObj = {
  name: "John",
  sayHello: function() {
    console.log("Hello, " + this.name + "!");
  }
};

In a constructor function, the this keyword is used to refer to the object being created. For example:

function Person(name) {
  this.name = name;
  this.sayHello = function() {
    console.log("Hello, " + this.name + "!");
  };
}

let person1 = new Person("John");
let person2 = new Person("Jane");

In this case, this refers to the object being created (person1 or person2).

#### Object Prototypes Using A Constructor

**Prototypes** in JavaScript can be thought of as blueprints for objects. Just as blueprints are used to build and customize a physical object, prototypes are used to create and customize JavaScript objects. Inheritance in JavaScript is the ability for an object to acquire properties and methods from another object. It's similar to the way children inherit certain traits and characteristics from their parents. For example, creating my personal projects for my portfolio, it will have its first model, and each day I will update the porfolio and add more as weeks goes. This will be much better but still if I need to re-do I have my first model as a starting point. 

**Inheritance** is a way of creating a new object based on an existing object. It allows you to define a new object that inherits all the properties and methods of an existing object, and then add or override properties and methods as needed. For example, if I want to add a differen theme to my page I will go ahead add a new color background and other new buttons, but never changing the whole web page from scratch, we keep the same layout but just updating new colors and buttons. Same goes as trainin a new employees, they just need to be trained but all job requirement are still the same just training a new personnel.

**Question**

Why do we need learn DOM modeling ?
What are HTML table and the reason semantics are utilize for our web page?
What is thead? Why is this use for tables in HTML?
What funtion is constructor and why we use it?












