---
title: How to Get Started with React.js
categories: [Programming]
tags: [JavaScript, React.js]
---

React.js has become one of the most popular JavaScript libraries for building user interfaces. It's lightweight, fast, and efficient, and has gained popularity among developers worldwide. If you're new to React.js or want to refresh your knowledge, then this post is for you. We'll explore the basics of React, how to set up a development environment, and how to get started with building a simple React app.

## Installing React

Before getting started with React, you'll need to install Node.js, which is a JavaScript runtime environment. Once you've installed Node.js, you can use the Node Package Manager (npm) to install React. Open your terminal or command prompt and enter the following command:

```
npm install react
```

This will install React and its dependencies into your project. Next, you'll need to install a package called ReactDOM, which provides React-specific methods for working with the DOM. Enter the following command:

```
npm install react-dom
```

## Setting Up a Development Environment

To create a new React project, you can use a tool called Create React App. This tool sets up a new React project with all the necessary dependencies and configuration files. To install it, run the following command:

```
npm install -g create-react-app
```

Next, you can use Create React App to create a new project. Navigate to the directory where you want your project to be created and enter the following command:

```
create-react-app my-app
```

This will create a new React project called "my-app" in the current directory. Once the project has been created, navigate into the project directory by running:

```
cd my-app
```

Finally, start the development server by running:

```
npm start
```

This will start a local development server at http://localhost:3000, and you'll see the default React app in your browser.

## Building a Simple React App

Now that you've set up your development environment, let's build a simple React app. Open your project in your preferred code editor, and navigate to the `src` folder. Inside this folder, you'll find two files: `index.js` and `App.js`.

`index.js` is the entry point for your React app, and it renders the `App` component. The `App` component is defined in `App.js`, and it's where you'll write your React code. Let's update `App.js` to display a simple message.

```javascript
import React from 'react';

function App() {
  return (
    <div>
      <h1>Hello, world!</h1>
    </div>
  );
}

export default App;
```

Here, we've imported the `React` library and defined a new function called `App`. This function returns a `div` element with an `h1` element inside. This will display the message "Hello, world!" in your app.

Now, save this file and go back to your browser. You should see the updated app with your message displayed. Congratulations, you've built your first React app!

## Conclusion

React.js is a powerful and flexible library for building user interfaces. In this post, we've explored the basics of React, how to set up a development environment, and how to build a simple React app. There's a lot more to learn, but this should be a good starting point for anyone new to React. Happy coding!