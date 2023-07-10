# Redux - Asynchronous Actions

## [async actions](https://redux.js.org/advanced/asyncactions)

1. Why use Redux middleware?

Redux middleware allows you to write async logic without including side effects in your reducers. The middleware also has access to dispatch and getState which makes it more flexible.

2. Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.

Rather than a button press dispatching a function that returns an action we are now dispatching a function that makes a request and then sends an action

3. How are we accommodating async in our Redux app?

We accommodate async in redux by using middleware and action creator patterns. We create functions that create custom 'thunk' functions that handle async data and then dispatch custom actions themselves without the components needing to know how to handle the data, and only need to dispatch a function.

## [thunk middleware](https://github.com/reduxjs/redux-thunk)

1. Why would you need `redux-thunk` middleware?

Thunk middleware for Redux allows writing functions with logic inside that can interact with a Redux store's dispatch and getState methods asynchronously.

2. Redux Thunk middleware allows you to write action creators that return a **Function** instead of an action.

3. Describe how any return value from the inner thunk function will be made available.

The return value from the inner thunk is made available by dispatching an action with the values from async data changes and updating the state

### What are your learning goals after reading and reviewing the [class README?](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-38/)

I guess the thunk middleware really really wasn't making sense. It seems unnecessary to use middleware when we are already defining 'action generators' that simply return an action. Why not just put the async logic in there? It makes some more sense after seeing a simple demo in this README. The `thunk` returns a promise that will resolve with an action. That makes a whole lot more sense than all of the roundabout explanations of the docs. The thunk middleware simply separates the functions that are returned from action generators from the actions. These difference generators are called action creators? I believe.
