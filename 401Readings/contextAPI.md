# Context API

## [Choosing the State Structure](https://react.dev/learn/choosing-the-state-structure)

1.  Summarize the five principles for structuring state.

1.  Group related state. If you always update two or more state variables at the same time, consider merging them into a single state variable.
1.  Avoid contradictions in state. When the state is structured in a way that several pieces of state may contradict and “disagree” with each other, you leave room for mistakes. Try to avoid this.
1.  Avoid redundant state. If you can calculate some information from the component’s props or its existing state variables during rendering, you should not put that information into that component’s state.
1.  Avoid duplication in state. When the same data is duplicated between multiple state variables, or within nested objects, it is difficult to keep them in sync. Reduce duplication when you can.
1.  Avoid deeply nested state. Deeply hierarchical state is not very convenient to update. When possible, prefer to structure state in a flat way.

## [Passing State Deeply with Context](https://react.dev/learn/passing-data-deeply-with-context)

1.  What problem do Contexts aim to solve?

Prop drilling and over using the ability to pass props to specific components without being able to skip to where you need it.

2.  What is one technique to try before useContext?

Before implementing useContext just try passing props. Even if it seems like a lot you should still try it because it may be more direct and helpful to pass.

3.  What hook complements useContext for complex applications?

the useReducer hook can compliment useContext for complex applications by allowing the state of a context to be mutated from one function and the state of the context to be kept in one place.

### Bookmark and Review

Keep these pages handy - they answer questions that show up regularly for this lab.

[Sharing State Between Components](https://react.dev/learn/sharing-state-between-components) [Preserving and Restting State](https://react.dev/learn/preserving-and-resetting-state)

#### Reflection

UseContext is an amazing asset to the react ecosystem, I often find myself trying to decide to pass or create a context for my state in one place. My apps are generally not complex enough to need a context that doesn't fit inside of my App.jsx, however using context for individual component trees may even be necessary as the scale of an app grows and its cool to see how useful it is.
