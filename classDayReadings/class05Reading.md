# Putting it all together

## Why this matters

- Learning how to "think in react" and understanding higher order functions is important (before) even reading) because building apps, correctly using and understanding code paradigms, and writing, functional or class based code are all in-depth concepts that require a deep understanding of the tools you are using and problems they are solving. Thinking "in" react means effectively giving components function and UI, while managing state with and between them, its complex and intertwined. It's important.

### [React Docs - Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

1. What is the single responsibility principle and how does it apply to components?

   - The single responsibility principle states that every class, module, or function in a program should have **one responsibility or purpose**.
     In relation to components: " a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller sub-components" (React docs).

2. What does it mean to build a ‘static’ version of your application?

   - "building a static version of the application means building a website with no interactivity" (React Docs)

3. Once you have a static application, what do you need to add?

   - a minimal representation of mutable (changeable) state that your app needs. Basically. The bare minimum to make your static "skeleton" properly interactive.

4. What are the three questions you can ask to determine if something is state?

   1. Is it passed in from a parent via props?
   2. Does it remain unchanged over time?
   3. Can you compute it based on any other state or props in your component?
   4. **If yes to any of these... It's _not_ state**

5. How can you identify where state needs to live?

   - For each piece of state in your application:

   - Identify every component that renders something based on that state.

   - Find a common owner component (a single component above all the components that need the state in the hierarchy).

   - Either the common owner or another component higher up in the hierarchy should own the state.

   - If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

   - _basically state should be "higher up" because everything should **only** be passed down. Therefore the best place to put state is as high as the state can go before it no longer has any **components in common**. And if nothing like this exists near where the common components lay, then a component should be made to hold that state and pass it to those common components._

### [Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

1. What is a “higher-order function”?
   - a higher order function is a function that "operates" on other functions by either taking them as arguments (like a callback) or returning them.
2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

   ```javascript
   // takes a number
   function greaterThan(n) {
    return m => m > n
    // returns the result of an anonymous arrow function checking if: m (argument from higher order function) is greater than n (argument from function being called currently) ??
   }
   ```

3. Explain how either map or reduce operates, with regards to higher-order functions.
   - the map function takes in a "callback" and applies that computation to each element in an array by looping through it. Then returns the new array with mutated values

## Things I want to know more about

- How to use reduce() to solve challenge 11 on today's code challenge.
- what exactly is _m_ in the greaterThan function??
