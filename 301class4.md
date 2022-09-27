[Home](/README.md)

# Class 04 - React and Forms

## React Docs - Forms

1. What is a ‘Controlled Component’?  
   A Controlled Component is a form element whose value is controlled by React by storing the value in state property and updating with setState().

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.  
   It depends on what we plan to do with the input. For example, we can use a handleChange() event handler to update the value as the user is typing to return search results that include the characters they typed. An example of waiting to update the value until they submit the form would be when they enter a username.

3. How do we target what the user is entering if we have an event handler on an input field?  
    We target the value entered by using `event.target.value`.

   ```js
    handleChange(event) {
        this.setState({value: event.target.value});
    }
   ```

## The Conditional (Ternary) Operator Explained

1. Why would we use a ternary operator?  
    Ternary operator used in place of a conditional if statement. We wouls use it to decrease the size of our code while returning the same result.
2. Rewrite the following statement using a ternary statement:

```js
if(x===y){
  console.log(true);
} else {
  console.log(false);
}
```

```js
x===y ? console.log(true) : console.log(false);
```

## Bookmark and Review

- [React Bootstrap - Forms](https://react-bootstrap.github.io/forms/overview/)
- [React Docs - conditional rendering](https://reactjs.org/docs/conditional-rendering.html)
