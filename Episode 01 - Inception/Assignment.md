## Namaste React Course by Akshay Saini

# _Episode 01 - Inception_

## Theory :

- What is `Emmet`? 

--> Emmet is a web-developer's toolkit that can greatly improve your HTML & CSS workflow: <! doctype html> <html lang="en"> <head> <title>Demo</title> </head> <body> </body> </html> <! doctype html>

- What is `CDN`? Why do we `use` it?

--> CDN links stand for Content Delivery Network Links. These links are used to connect CSS frameworks or scripts; basically, already-written code can be connected through these links.

- Why is `React known as React`?

--> It "reacts" quickly to changes without reloading the whole page. It uses the virtual DOM to efficiently update parts of a webpage. It's built around components that "react" and update.

- What is `crossorigin in script tag`?

--> The HTML <script> tag with the crossorigin attribute specifies how to handle fetching of external scripts. When set to “anonymous”, it indicates that the script should be retrieved without sending user credentials.

--> The purpose of crossorigin attribute is used to share the resources from one domain to another domain. Basically, it is used to handle the CORS request. It is used to handle the CORS request that checks whether it is safe to allow for sharing the resources from other domains. The resources may include Audio, Video, Images, Link or external script that specifies whether to support a cross-origin request or not.

- What is difference between `React and ReactDOM`?

--> While React provides the tools and concepts to define component-based user interfaces, ReactDOM handles the task of rendering those interfaces in a web environment. Together, they form the foundation of React web applications.

- What is difference between `react.development.js` and `react.production.js` files via CDN?

--> When using React with CDN links, it’s important to understand the differences between the development (dev) and production (prod) links and when to use them appropriately. You should not use them interchangeably, as each is optimized for a specific purpose.

--> Development (Dev) Link:
* The development link is typically used during the development phase of your application.
* It includes additional debugging tools, warnings, and helpful error messages.
* It is larger in file size and may negatively impact the performance of your application.
* It is not optimised for production use.

vice versa ........

- Why React is a Library Not a Framework ?

--> Because it can work independently in small portion of App as well. it is not fully fledged framework.

--> A Framework is a framework which comes with all loads of things. A framework comes with lots of package in it. React is a barebone minimum javascript library, it is just some piece of javascript code which is written by facebook developer.

--> Libraries provide developers with predefined functions and classes to make their work easier and boost the development process. Framework, on the other hand, is like the foundation upon which developers build applications for specific platforms.

- createElement. createElement lets you create a React element. It serves as an alternative to writing JSX.

- What is the difference between createElement and JSX?
--> React.createElement() vs JSX — Phuoc Nguyen
One of the key differences between JSX and `React. createElement()` is that JSX lets you write your HTML-like code directly in your JavaScript file. On the other hand, with `React. createElement()` , you need to pass the element type, props, and children as separate arguments.

- createRoot. createRoot lets you create a root to display React components inside a browser DOM node. const root = createRoot(domNode, options?).

- In React, Render is the technique that can redirect a page with the help of function render(). Most importantly, render a function we can use to define the HTML code within the HTML element. It helps to display certain views in the UI using certain logic defined in the render function and returns the output.

## Coding :

- Set up all the `tools in your laptop`
  - `VS Code`
  - `Chrome`
  - `Extensions of Chrome`
- Create a `new Git repo`
- Build your `first Hello World` program using,
  - Using `just HTML`
  - Using `JS to manipulate the DOM`
  - Using `React`
    - use `CDN Links`
    - Create `an Element`
    - Create `nested React Elements`
    - Use `root.render` -> It is just putting parent (parent) inside root tag. root. render() is used to render a React component into the DOM.
- `Push code to Github` (Theory as well as code)
- Learn about `Arrow Functions` before the next class

## References:

- https://beta.reactjs.org/apis/react/createElement
- https://www.youtube.com/watch?v=IrHmpdORLu8
