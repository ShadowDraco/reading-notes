# React Forms and controlled components

## Reading

### [React Docs - Forms](https://reactjs.org/docs/forms.html)

- What is a ‘Controlled Component’?

  - A controlled component is a component that is managed by state in react.
    updates from the component update state and then display the changes

- Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

  - Components can be controlled and update and store state at every change, but form submissions should only send data after the form is filled out. This gives the server a complete set of data to check and then send information back, rather than constantly sending data to the API or server (etc) and causing problematic and expensive calls.

- How do we target what the user is entering if we have an event handler on an input field?
  - Pass the event to the function that manages the state.

```javascript
  handleChange(**event**) {

  }
```

### [The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

- Why would we use a ternary operator?
  - Ternary operators are flexible, easy to read, and concise. If statements are not obsolete but a ternary operator can accomplish a great deal! _They are very useful even for complex logic functions_, \***\*so long as each condition returns a single value.**
- Rewrite the following statement using a ternary statement:

```javascript

if(x===y){
console.log(true);
} else {
console.log(false);
}

// easily refactor into a single line statement
----> x===y? console.log(true) : console.log(false)

```
