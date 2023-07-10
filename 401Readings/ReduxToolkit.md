# Redux - Additional Topics

## [Redux Toolkit (RTK)](https://redux-toolkit.js.org/introduction/getting-started)

1. What concerns are addressed by Redux Toolkit?

"Configuring a Redux store is too complicated"
"I have to add a lot of packages to get Redux to do anything useful"
"Redux requires too much boilerplate code"

2. What does `configureStore()` do?

wraps createStore to provide simplified configuration options and good defaults. It can automatically combine your slice reducers, adds whatever Redux middleware you supply, includes redux-thunk by default, and enables use of the Redux DevTools Extension.

3. How would I use `createSlice()`?

a slice is a combined reducer for a specific art of the state tree, My todos will have reducers combined into a slice and my toNots will have reducers combined in a slice. They are combined as key-function pairs. Generally having the same name

## [MobX](https://mobx.js.org/getting-started.html)

1. What is Mobx?

MobX is a simple, scalable and battle tested state management solution.

2. How does MobX make it "impossible" to produce an inconsistent state?

MobX will make sure that all changes to the application state caused by your actions are automatically processed by all derivations and reactions. Synchronously and glitch-free.

3. How would we build a reactive user interface?

making a react interface is in general the same, though there is no need for dispatching and useSelecter-ing everting, we just assign functions to components with observers and the state is managed.

[Tutorial](https://redux-toolkit.js.org/tutorials/intermediate-tutorial)

1. What take-away(s) did this tutorial provide?

The redux toolkit provides extra APIS to simplify working with redux, make it more concise and remove a lot of extra boilerplate code. It greatly helps with keeping state management in one import and export at a time

[Redux Toolkit (RTK)](https://redux-toolkit.js.org/)

[HookState](https://hookstate.js.org/)

## Reflection

1. What are your learning goals after reading and reviewing the [class README?](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-39/)

Learning an alternative state management to redux seems pretty cool, I think extensions to redux at this time seems like a better option but I enjoy seeing the world of state management open up when I didn't even know there were other tools out there yesterday
