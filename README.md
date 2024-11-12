## React JS

### What is React JS?
- React JS, commonly referred to as React, is a JavaScript library developed by Facebook for building user interfaces (UIs).
- React is a declarative, component-based library that
allows developers to build reusable UI components.

### Key Features of React

- #### Component-Based Architecture
    - React enables developers to break down the UI
    into smaller, self-contained components

- #### JSX (JavaScript Syntax Extension)
    - JSX is a syntax extension for JavaScript that allows developers to write HTML-like code within their JavaScript files. This makes React components more readable and expressive. For example:
``const name = "GeekforGeeks";``
``const element = <h1>Welcome to {name}</h1>;``
    - JSX is not mandatory but is highly recommended for its readability and ease of use

- #### Virtual DOM
    - React maintains a lightweight representation of the actual DOM in memory. When changes occur, React efficiently updates only the necessary parts of the DOM, improving performance

- #### One-Way Data Binding
    - React follows a one-way data binding approach, where data flows from parent components to child components. This makes it easier to understand and debug the application

- #### Performance
    - React's use of the virtual DOM and efficient updating mechanisms make it a fast and performant library for building UIs

- #### Single-Page Applications (SPAs)
    - React is often used to create SPAs, which allow for smooth content updates without page reloads. This is ideal for real-time applications

---

### How React Works
- React operates by creating an in-memory virtual DOM rather than directly manipulating the browser’s DOM. It performs necessary manipulations within this virtual representation before applying changes to the actual browser DOM. This approach minimizes DOM updates and enhances performance

---

### How to Install React
**Step 1**: Install Node.js
1. To install Node, visit the [Node.js](https://nodejs.org/en/).
2, Once installation is complete, open your command prompt to confirm that Node has been successfully installed. Type in `node - v` in your command prompt, then enter. Move to the step 2 if the Node version is displayed in the command prompt.

**Step 2**: Install React
**Using CRA (Traditional)**
1. type `cd [directory name]` then enter.
2. In the documents directory (or wherever you're creating your project), create a folder that you will be using to create your React app. Type `mkdir [folder name]`then navigate to the newly created directory using cd [newly created folder name].
3. In the newly created folder directory, type in `npx create-react-app [project name of your choice]`, and then wait until your React project is completely created. 
4. Lastly, open the React project in your code editor by typing in `code .`. 

**Using Vite (Modern)**
1. Make sure the Node is installed.
2. Navigate to the directory you want to use and create a new folder.
3. Open the terminal (located in between Run and Help), then run `npm create vite@latest[your project name]`.
4. *Select Framework* - use cursor to navigate to where we have React,then enter.
5. *Select Language* - choose JavaScript
6. Navigate the project directory where you created the React project. Type `cd [directory name].
7. Install the Node module folder by typing `npm install`in the terminal. Once it is done, you should see the folder at the top.
8. Type `npm run dev`to run your project and display on the web page. 

---

### References: 
<https://www.w3schools.com/whatis/whatis_react.asp>
<https://www.geeksforgeeks.org/reactjs-introduction/>
<https://www.freecodecamp.org/news/how-to-install-react-a-step-by-step-guide/>
