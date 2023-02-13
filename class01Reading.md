# Class 01 Reading assignment

1. ## [Component based Architecture](https://www.tutorialspoint.com/software_architecture_design/component_based_architecture.htm)

   - Component based architecture focuses on decomposing the design of a webpage into function or logical components.
     This: - provides a higher level of abstraction - and divides problems into sub problems

   1. What is a component?

      - "A modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher level interface."
        or a flexible interface that has its own purpose which is reusable and accessible. It can be used independently or in conjunction with other components and software.

   2. What are the characteristics of a component?

      - _Reusable, replaceable, not context specific, extensible, encapsulated, independent_.

   3. What are the _advantages_ of using component-based architecture?

      - Ease of deployment, reduced cost, ease of redeployment and editing, reusable, modification of complexity, reliable, easy to maintain and grow, flexible, and independent allowing for self-sustained usage or incorporation elsewhere.

2. ## [What is props and how to use it in react](https://itnext.io/what-is-props-and-how-to-use-it-in-react-da307f500da0#:~:text=%E2%80%9CProps%E2%80%9D%20is%20a%20special%20keyword,way%20from%20parent%20to%20child)

   - React is a component-based library that divides the UI into pieces and allows them to send data to each other.
     - Achieve this using **props**

   1. What is 'props' short for

      - "Props" is a special react keyword short for **_Properties_**

   2. How are props used in react?

      - Props are used as a uni-directional, read only way of passing data to child components. They are used for rendering data, but not for updating. This is called _Read only_

   3. What is the flow of props?

      - _uni-directional_ means the flow of data is **only** child to parent

## Things I want to know more about

- Props and providing state up and down in props using things like useContext which provides to all children. Is there any other method for sharing props? I've seen useQuery but have not made a project that implement it yet

- How does JSX prevent injection attacks and keep things safe really? I still have to take precautions for getting user data and saving it and letting users run functions in the backend. But not to take it and display it on the front end because JSX escapes it?

- callback functions are a "function that you don't call" it is used by the function you provide it to like forEach((item, index) => {
  callBack()
  })
