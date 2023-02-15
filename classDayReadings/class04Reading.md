# React Forms and controlled components

## Why this is important

> Knowning how to use controlled components is very valuable in react because simple html elements can handle their own little 'state' in an input field, but with react you need actual **state** to manage this data because it is supposed to remain persistent, while having the ability to update and rerender.

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

## Things I want to know more about

> I want to know more about how to run complex logic with nested ternary operators, and how the `something? & something` works. I believe there is also the or operation like `something || somethingElse` which can display things in components or be used in vanilla javascript.
> Specifically are ternary operators truly limited to single condition to single return statements? or are they more powerful than that. Because I don't believe that if and else statements are useless. As well as the use cases for & and |.
