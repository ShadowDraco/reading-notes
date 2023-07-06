# Redux - Combined Reducers

## [Multiple Reducers Example](https://www.youtube.com/watch?v=gBER4Or86hE)

1. Why create multiple reducers?

   Multiple reducers makes state management easy to use in many places and reinforces single responsibility and a requirement for pure functions

2. How would you combine multiple reducers?

   combining reducers seems to work by replacing `action`, `type`, and `payload` with `reducer` and `payload` by way of allowing multiple reducer functions to be exported from one place, they will all manage one action and remain pure and predictable functions

3. How will you manage state as an immutable object? why?

   State is immutable which means it is read only and cannot be changed. The way to change the state is to make a copy, update it and then save it that way.

## [Redux Docs: Using Combined Reducers](https://redux.js.org/recipes/structuring-reducers/using-combinereducers/)

1. `combineReducers` is a utility function to simplify the most common use case when writing **Reducers**.

2. Explain how `combineReducers` assembles the new state tree.

`combineReducers` takes in slices of reducers that each manage their own little pieces of state and combines them into an object with keys of the reducer name, and values of the reducer function. This allows you to import all reducers into multiple places from one place.

3. How would you define initial state in an app using `combineReducers`?

Defining initial state in an app using combineReducers can be done by setting initial state in each reducer before combining them or taking initial state from somewhere else, like local storage

## [Redux Docs: Combined Reducer Syntax](https://redux.js.org/api/combinereducers/)

1. Why will you want to split your reducing functions as your app becomes more complex?

Splitting up the reducer functions allows state from multiple places to be easily and more readably managed, it keeps reducers managing only their own little slicers and keeps from importing too many reducers at once.

2. The **`combineReducers`** helper function turns an object whose values are different reducing functions into a single reducing function you can pass to **`createStore`**.

3. What is a popular convention when naming reducers?


It's common to name reducers after the slice of state they manage.

### Reflection

1. What are your learning goals after reading and reviewing the [class README?](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-37/)

Combining reducers seems like a pretty complex concept considering how big and different react redux is. However it seems pretty cool, so learning how to make functions generalized and componetized even further will be cool, making the state management process take in action, payload, and reducer to use it with makes everything very custom and controllable
