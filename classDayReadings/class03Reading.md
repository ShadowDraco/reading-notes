# Passing functions as props

Reading
[React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)

- What does .map() return?

  - `map` returns a new array, or a _component_ if used in react

- If I want to loop through an array and display each value in JSX, how do I do that in React?

```jsx
//Create a a jsx scope with curly braces and map through the array
{
	arr.map(element => {
		// Return the element to display
		return <CustomElement key={element.number}> {element.text} </CustomElement>
	})
}
//Be sure to provide a key to each unique list item returned from map
```

- Each list item needs a unique **_key_**.
- What is the purpose of a key?
  - keys help react identify what elements are updating and changing and identify elements from their siblings

[The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

- What is the spread operator?

  - the spread operator uses an **ellipsis** of **three dots** `...` to expand or _spread_ an iterable _(loopable)_ object into a list of arguments

- List 4 things that the spread operator can do.

  - The spread operator assists in **copying arrays, combining arrays, adding items to lists/arrays, using arrays as arguments, updating state in react, combining objects, using math functions, and more**

- Give an example of using the spread operator to combine two arrays.
  `arrThree = [...R2, ...D2];`

- Give an example of using the spread operator to add a new item to an array.
  `arrThree = [...arrThree, BB] // --> arrThree: [R2, D2, BB]`

- Give an example of using the spread operator to combine two objects into one.

  ```javascript
  obj1 = { hello: 'there' }
  obj2 = { my: 'friend' }

  obj3 = { ...obj1, ...obj2 } // {hello: 'there', my: 'friend'}
  ```

Videos

[How to Pass Functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)

- In the video, what is the first step that the developer does to pass functions between components?

  - the first step is to create a function at the parent level (the same component that has the state you want to pass)

- In your own words, what does the increment function do?

  - increment takes a person's name, loops through a list of people, finds the correct person, and updates that person's count.

- How can you pass a method from a parent component into a child component?
  - pass the function to the child as a prop
- How does the child component invoke a method that was passed to it from a parent component?
  - the child invokes the function my calling the function from _this.props_
