# : Application State with Redux

## [Dan Abramov Redux Tutorials](https://egghead.io/courses/getting-started-with-redux)

1.  What is the first principle of Redux?

- Redux provides a solid, stable, and mature solution to managing state in your React application.

2.  what is a store and what do we use our reducers for within that store?

- The store in redux is a special implementation of react state management that leverages many new built in methods and features. The redux store uses reducers to maintain state and keep all state management functions pure.

3.  Name three Redux store methods given to us by createStore and describe
    their use.

- The three store methods are `getState()` `dispatch()` and `subscribe()`
  getState retrieves the current state of the Redux store. The dispatch function takes in an action and a payload and mutates state in a pure way
  The subscribe function lets you register a callback that the Redux chore will call any time an action has been dispatched, so that you can update the UI of your application. It will reflect the current application state.

4.  Explain to a non-technical recruiter what `combineReducers()` does and why it is useful.

- the combineReducers function takes in some directions to create a reducer function for parts of state. This saves on writing a lot of code for various combined state interactions by systematically combining the functions that manage multiple parts of the information the page uses together.

;

[worlds easiest guide to redux](https://medium.freecodecamp.org/understanding-redux-the-worlds-easiest-guide-to-beginning-redux-c695f45546f6)

[testing reducers](https://medium.com/@netxm/testing-redux-reducers-with-jest-6653abbfe3e1)

[Redux Docs](https://redux.js.org/)

-

### 1. Looking ahead at this module's [course schedule](https://codefellows.github.io/code-401-javascript-guide/curriculum/#module-8), What do you look forward to learning?

- I've heard a lot about Redux and i'm excited to finally learn it, though I think it will be quite a difficult topic once again so im also looking forward to reviewing how it works before we state doing it in class

### 2. What are your learning goals after reading and reviewing the [class

README?](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-36/)

My goal is to create and explain the proof of life for redux and its actions/behaviors