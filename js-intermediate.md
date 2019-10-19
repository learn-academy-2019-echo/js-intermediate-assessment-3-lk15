# ASSESSMENT 3: INTERMEDIATE JAVASCRIPT
## Interview Practice Questions

Answer the following questions. First, without external resources. Challenge yourself to answer from memory. Then, research the question to expand on your answer. Even if you feel you have answered the question completely on your own, there is always something more to learn.

1. What are the HTTP verbs? Which CRUD action corresponds to each verb?

  Your answer:
  Get - Read
  Post - Create
  Delete - Delete

  Researched answer:
  Get - read
  Post - create
  Put - update
  Patch - update
  Delete - delete


2. Why would you use object destructuring?

  Your answer: To make code easier to read

  Researched answer: Object destructuring allows us to use more compact syntax. It is useful with nested objects and so can be especially useful in React JS as often times variables are nested in props or state.
  
  Reference: https://wesbos.com/destructuring-objects/


3. Why is testing important?

  Your answer: Testing is important to make sure that code is functioning properly and to catch bugs.

  Researched answer:
  - Break down problems into smaller pieces
  - Avoid feature creep - stay focused on essential piece of the program
  - Keeps focus on the current objective
  - Tests can save you lots of time bug fixing a new feature


4. What is the difference between a class and an object?

  Your answer: A class can be used to create other objects.

  Researched answer: Classes are like blueprints for objects, with a constructor function that can be used to create an object. An object is an instance of a class.


5. What did you learn during the group project this week? Please include any additional feedback you may have.

  Your answer: I learned about using React in a real world application. I was sick on the second day of the tic tac toe group project so am not able to give a lot of feedback. 



### HTML/CSS Review questions: First, try to answer each question on your own then Google the answer to further your knowledge.

1. How do you link a CSS file to your HTML page?

  Your answer: In the head section you would link to your stylesheet

  Researched answer:
  <link href="cssfilename.css" rel="stylesheet" type="text/css">


2. What is the difference between a div and a span?

  Your answer: A div is a block of content. A span is an inline area of content.

  Researched answer: "The difference between span and div is that a span element is in-line and usually used for a small chunk of HTML inside a line (such as inside a paragraph) whereas a div (division) element is block-line (which is basically equivalent to having a line-break before and after it) and used to group larger chunks of code."
  
  Reference: https://htmldog.com/guides/html/intermediate/spandiv/


3. What is a CSS class? When should you use an id instead of a class?

  Your answer: A CSS class is used to apply the same style to multiple items. An id would be used to apply a certain style to an individual item.

  Researched answer: "The difference between an ID and a class is that an ID can be used to identify one element, whereas a class can be used to identify more than one."
  
  Reference: https://htmldog.com/guides/css/intermediate/classid/


4. Name 4 semantic HTML tags.

  Your answer: <header> <footer> <section> <aside>

  Researched answer:
  <article>
  <aside>
  <details>
  <figcaption>
  <figure>
  <footer>
  <header>
  <main>
  <mark>
  <nav>
  <section>
  <summary>
  <time>


5. What are three options for creating responsive design?

  Your answer:
  - using media queries
  - flexible images and content
  

  Researched answer:
  - Use a Framework such as Bootstrap
  - Hiding content on smaller screens
  - set the viewport <meta name="viewport" content="width=device-width, initial-scale=1.0">
  - Flexible grid


### STRETCH: The following questions are potential interview questions. First, try to answer each question on your own then Google the answer to further your knowledge.

1. What is front end development? Can you identify any tools/skills that are uniquely required of front end developers?

  Your answer: Front end development is developing the client facing aspect of a website or application. Front end developers in some cases also incorporates a designer role, while in other cases work alongside designers to develop a project. Front end developers require knowledge of HTML/CSS, and client-side languages such as JavaScript. They also need to be able to work collaboratively with designers and other members of their team.

  Researched answer: The front end of a website is the part that users interact with. Front-end developers must be adept at HTML, CSS, and Javascript. They should also be familiar with frameworks such as Bootstrap, Foundation, Backbone, AngularJS, and EmberJS and libraries like jQuery and LESS. A lot of front-end developer job listings also call for experience with Ajax, a widely used technique for using Javascript that lets pages dynamically load by downloading server data in the background.
  
  Front-end developers work closely with designers or user experience analysts. Strong front-end developers can also accurately identify specific issues in user experience and provide recommendations and codified solutions to influence the design. It’s also important to be able to fluidly partner with other teams across the business to understand specific goals, needs, and opportunities, and then execute on those directives.
  
  Reference: https://blog.udacity.com/2014/12/front-end-vs-back-end-vs-full-stack-web-developers.html


2. What is block scope in JavaScript?

  Your answer: Not sure

  Researched answer: Var has function scope (if it is defined within a function, it is not available outside the function. If it is defined outside a function it globally scoped). Var is not limited to the curly brackets, the function defines the scope. Let and const on the other hand are block scoped. A block is a set of open and closing curly brackets.
  
  References: 
  https://medium.com/@josephcardillo/the-difference-between-function-and-block-scope-in-javascript-4296b2322abe
  https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/block
  


3. How would you explain the idea of "inheritance" in object oriented programming?

  Your answer: An object inherits the characteristics of its class

  Researched answer: "In object-oriented programming, inheritance is the mechanism of basing an object or class upon another object (prototype-based inheritance) or class (class-based inheritance), retaining similar implementation. Also defined as deriving new classes (sub classes) from existing ones (super class or base class) and forming them into a hierarchy of classes. In most class-based object-oriented languages, an object created through inheritance (a "child object") acquires all the properties and behaviors of the parent object (except: constructors, destructor, overloaded operators and friend functions of the base class). Inheritance allows programmers to create classes that are built upon existing classes,[1] to specify a new implementation while maintaining the same behaviors (realizing an interface), to reuse code and to independently extend original software via public classes and interfaces."
  
  Reference: https://en.wikipedia.org/wiki/Inheritance_(object-oriented_programming)
