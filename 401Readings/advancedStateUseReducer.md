# Advanced State - Use Reducer Hook

## [Extracting State Logic into a Reducer](https://react.dev/learn/extracting-state-logic-into-a-reducer)

1.  What is the motivation for adding a reducer?

Components with many state updates spread across many event handlers can get overwhelming. For these cases, you can consolidate all the state update logic outside your component in a single function, called a reducer.

2.  What are actions in the context of a reducer? How are they different than setting state directly?

Managing state with reducers is slightly different from directly setting state. Instead of telling React “what to do” by setting state, you specify “what the user just did” by dispatching “actions” from your event handlers. (The state update logic will live elsewhere!) So instead of “setting tasks” via an event handler, you’re dispatching an “added/changed/deleted a task” action. This is more descriptive of the user’s intent.

3.  What common list operation is useReduce named for, and why?

they are actually named after the reduce() operation that you can perform on arrays.
The reduce() operation lets you take an array and “accumulate” a single value out of many:

4.  When should you switch from useState to useReducer?

useReducer is best when you have a lot of complex state that is being handled and set from many places

## Bookmark and Review

Keep these pages handy - they answer questions that show up regularly for this lab.

- [useReducer hook](https://react.dev/reference/react/useReducer)
- [Keeping Components Pure](https://react.dev/learn/keeping-components-pure)
- [Queueing a Series of State Updates](https://react.dev/learn/queueing-a-series-of-state-updates)

## Reflection

1.  What are your learning goals after reading and reviewing the [class README?](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-29/)

I've never tried useReducer before or even looked into it so I'm not toooo excited to try it knowing it might be a hassle haaha, but I really want to learn more about it!
