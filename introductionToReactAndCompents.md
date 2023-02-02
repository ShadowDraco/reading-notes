# Introduction to React and Components

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
