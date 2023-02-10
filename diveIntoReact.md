# React is an AGNOSTIC User Interface Library

meaning it doesn't care where the information comes from, it just creates a DOM and renders it
The react library **doesn't care** if you're using it in a browser or anywhere else, it only needs to have a second library like:
_ReactDOM - react360_ - etc that will help render

1. a react element is **_NOT a DOM element_**
   React does not become DOM until it is passed through ReactDOM [which converts it]

   - React is used to create **interfaces** - _graphs, bars, entire websites, applications, widgets_ etc - it can use for all of these things

   - React is a library

   - Frameworks come with functions and useful tools etc
   - but it is a library which is pretty lightweight and has functions for creating user interface

   - React components are modular and reusable
   - components can import other components to utilize them in a component tree

2. In component trees data flows down ONE WAY and this is important in the architecture of react

```------------------------ APP ------------------------
             Header                   content                footer
    site info     main nav                            copyright  footer nav


            Info flows ***Down***  *to* these components in the tree
```

- to update data for the bottom `<MainNav />` you can update data in `<Header />` and send it back down to `<MainNav />`

3. Review

   - **_React is a user interface library (UILib)_**

   1. Has Component Architecture
   2. Has data flow in one direction
   3. has "state" for its components

**_Every component manages its own State_**.
