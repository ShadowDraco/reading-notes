[Thinking in React](https://react.dev/learn/thinking-in-react)

1.  Summarize the five steps of thinking in react.

First you should break the UI into a component heirarchy. seperate the pieces of information and determine how to break them up and establish the relationships they have. Second, build a static version perhaps with some hard coded data. It's proof of life for the webpage and placeholders for functionality. find the least, but complete, representation of your UI to determine where state should live and how to connect it. After hooking up the downward prop drilling create an inverse data flow that allows nested components to update parent state.

[State: A Component's Memory](https://react.dev/learn/state-a-components-memory)

1.  What is one reason a local variable isn't sufficient for managing a React component?

Local variables are not persistent and if they were they still don't trigger rerenders of the DOM.

2.  What is the argument to the useState hook, and what are the two parts of its return array?

The useState hook takes in an _*Initial*_ value, and it returns the _State Variable_ and the _Setter function_.

3.  How can Component A access state from Component B?

Component A can access state from component B if **B** gives A permission by way of passing said state as a prop (parameter to the function that calls the component)

## Bookmark and Review

Keep these pages handy - they answer questions that show up regularly for this lab.

- [Passing Props to a Component](https://react.dev/learn/passing-props-to-a-component)
- [Rendering Lists](https://react.dev/learn/rendering-lists)
- [State as Snapshot](https://react.dev/learn/state-as-a-snapshot)
- [useState hook](https://react.dev/reference/react/useState)

## Reflection

1.  What are your learning goals after reading and reviewing the [class README?](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-27/)

Let's make some functional components functional!
