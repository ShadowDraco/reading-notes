# React is an AGNOSTIC User Interface Library

meaning it doesn't care where the information comes from, it just creates a DOM and renders it
The react library **doesn't care** if you're using it in a browser or anywhere else, it only needs to have a second library like:
_ReactDOM - react360_ - etc that will help render

-- a react element is **_NOT a DOM element_**
React does not become DOM until it is passed through ReactDOM [which converts it]

- React is used to create interfaces - graphs, bars, entire websites, applications, widget etc - it can use for all of these things

_React is a library_

- Frameworks come with functions and useful tools etc
- but it is a library which is pretty lightweight and has functions for creating user interface

- React components are modular and reusable
- components can import other components to utilize them in a component tree

-- In component trees data flows down ONE WAY and this is important in the achitecture of react

```------------------------ APP ------------------------
             Header                   content                footer
    site info     main nav                            copyright  footer nav
                                        Info flows down  to these compoentns in the tree
```

to update data for the bottom `<MainNav />` you can update data in `<Header />` and send it back down to `<MainNav />`

- Review

React is a user interface library UILib
Has Compenent Architecture
Has data flow in one direction
has "state" for its components
