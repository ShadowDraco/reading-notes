# React Use Effect Hook

## [useEffect hook](https://react.dev/reference/react/useEffect#reference)

1.  What is the main intended use case for the useEffect hook?

The React useEffect hook is primarily used for syncing a component with an external system. i.e an API

2.  How does the effect's logic interact with the component?

When the component is rendered and rerendered it calls the setup and cleanup code in the useEffect that is described _if one of the dependencies is affected during said rerender_ and this will alow the component to sync its data with other processe.

3.  What is the importance of the return value from the effect's logic function?

if the use effect returns nothing then nothing will stop. However if you use a cleanup function to return functions that turn off event listeners or cancel certain connections it will allow the app to not accidentally make calls/updates to or from unwanted processes/external sources. This may prevent unwanted API calls or even a simple unwanted onclick handler overdoing itself.

## Bookmark and Review

Keep these pages handy - they answer questions that show up regularly for this lab.

- [Responding to Events](https://react.dev/learn/responding-to-events)
- [Conditional Rendering](https://react.dev/learn/conditional-rendering)
- [Updating Arrays in State](https://react.dev/learn/updating-arrays-in-state)
- [Updating Objects in State](https://react.dev/learn/updating-objects-in-state)

### Reflection

1.  What are your learning goals after reading and reviewing the [class README?](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-28/)

useEffect is super cool and provides many many new possibilities to a basic app and I can't wait to start using it.
