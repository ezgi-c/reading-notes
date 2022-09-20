[Home](/README.md)

# Class 02 - State and Props

## React lifecycle

1. Based off the diagram, what happens first, the `render` or the `componentDidMount`?  
    `render` happens first.
2. What is the very first thing to happen in the lifecycle of React?  
    First thing in the lifecycle of a React component is calling the `constructor`.
3. Put the following things in the order that they happen: `componentDidMount`, `render`, `constructor`, `componentWillUnmount`, `React Updates`  
    `constructor` > `render` > `componentDidMount` > `React Updates` > `componentWillUnmount`
4. What does `componentDidMount` do?  
    `componentDidMount` method is invoked after a component is mounted. This is where we create subscriptions or perform network requests. 

## React State Vs Props

1. What types of things can you pass in the props?  
    Static information from a parent component that will not be changed insdie the child component. For example, properties of components such as title and description. 

1. What is the big difference between props and state?  
    props is passed into a component, states is not; and while state is handled inside the component, props is handled outside. 
1. When do we re-render our application?  
    When we change the state inside of the application, it re-renders that section. 
1. What are some examples of things that we could store in state?  
    We store values that can be updated, for example, user input in a form that can be updated by the user.

## Bookmark and Review

- [React Docs - State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)
- [React Docs - handling events](https://reactjs.org/docs/handling-events.html)
- [React Tutorial through ‘Developer Tools’](https://reactjs.org/tutorial/tutorial.html)
- [React Bootstrap Documentation](https://react-bootstrap.github.io/)
- [Boootstrap Cheatsheet](https://getbootstrap.com/docs/5.0/examples/cheatsheet/)
- [Bootstrap Shuffle - a class “sandbox”](https://bootstrapshuffle.com/classes)
- [Netlify](https://www.netlify.com/)
