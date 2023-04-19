# States and props!

**_Knowing about states and props is very important because it provides persistent data and the ability to pass that data around_**

## [React lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

1. Based off the diagram, what happens first, the _‘render’_ or the _‘componentDidMount’_?
   - _render_
2. What is the very first thing to happen in the lifecycle of React?
   - _constructor_
3. put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

   - _componentWillUnmount | constructor, render, react updates, component did mount_

4. What does componentDidMount do?

   - _component did mount gives an opportunity to pass updates to the component after its mounted and rendered. Subscriptions and API calls can be made and changing state will require a rerender_.

## [React State vs. Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

1. What types of things can you pass in the props?

   - _props can have objects, numbers, strings, arrays, etc._

2. What is the big difference between props and state?

   - _State is handled in the component and must be updated inside the component, while props are handled outside the component and passed in.
     props are generally for initial values and displaying variable information in components, and state is generally for tracking data that will change._

3. When do we re-render our application?

   - _rerendering happens after state changes and updates to props_

4. What are some examples of things that we could store in state?

   - _State can store updated input fields for a form, time in seconds from a clock component, clicks from a button component, usernames and health bars, objects or fields that are going to change but need to remain persistent._
