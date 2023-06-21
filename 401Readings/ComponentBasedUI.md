[React Quick Start](https://react.dev/learn)

Read the React Quick Start guide, to refresh your memory on React.

1.  What are the building blocks of a React app?

React Components make up an app by defining small pieces of the structure one at a time.

2.  What is the difference between an HTML element and a React component?

React components are functions that return markup, and must be capitalized with camel case. HTML is generally lowercased and is not combined with jsx or other javascript stuff.

3.  What is JSX and why do we use it?

JSX is a markup syntax that allows Javascript to be embedded into html. It is more strict but also more convenient

4.  Describe the process of embedding JavaScript expressions in JSX.

Embedding javascript is done by using curly braces to return components produced by some logic or embed some variables into an html space.

5.  Does React or JSX have any special features for iteration or conditional logic?

JSX does not support if statements or certain loop statements but does not include any special features for the logic or loops.

6.  How does React know to respond to a user's inputs?

event handler functions

7.  What word indicates that a React component manages data with a Hook?

the 'use' keyword is attached to every built in hook and is the best practice for defining your own hooks.

8.  How can two react components share data?

you can pass data 'state' through `props` one by one, which includes the desired variables as a parameter of the react component function, or use the useContext hook for a more accessible state.

[Render and Commit](https://react.dev/learn/render-and-commit)

1.  What are the three steps of refreshing a React UI?

The 3 steps to rendering a component are Trigger, render, and Commit.

2.  How do you trigger updates to a component after the initial render?

Rerenders occur after state updates.

3.  Does React recreate DOM nodes on every rerender?

React will reevaluate the existing DOM nodes on rerender but will not recreate them every time if unnecessary.

4.  After React has updated the DOM, what still needs to happen before the user sees the change?

After updating the DOM React has to commit the changes by appending the updated Child.

## Bookmark and Review

Keep these pages handy - they answer questions that show up regularly for this lab.

- [Your First Component](https://react.dev/learn/your-first-component)
- [Importing and Exporting Components](https://react.dev/learn/importing-and-exporting-components)
- [Writing Markup with JSX](https://react.dev/learn/writing-markup-with-jsx)

- [sass cheatsheet](https://devhints.io/sass)
- [react cheatsheet](https://devhints.io/react)

## Additional Questions

1. Looking ahead at this module's [course schedule](https://codefellows.github.io/code-401-javascript-guide/curriculum/#module-6), What do you look forward to learning?

new sort functions will be pretty challenging but learning useReducer will be great

2. What are your learning goals after reading and reviewing the [class README?](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-26/)

diving into functional components after building that non-functional-foundation will be great,
