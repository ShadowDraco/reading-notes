# Data Structures and algorithms

## [8 common data structures](https://towardsdatascience.com/8-common-data-structures-every-programmer-must-know-171acf6a1a42)

- Arrays

- Linked Lists

- Stacks

- Queues

- Hash tables

- Trees

- Heaps

- Graphs

## [Data structures in 15 minutes](https://www.youtube.com/watch?v=sVxBVvlnJsM)

- Data like the stock prices as they change over an entire day is called compound data

- Big O notation is the measure of how long it will take to do an operation as it scales

- Linked lists have a pointer, head, tail. Really good at adding and deleting, but not good at retrieving or searching

- Arrays are a continuous block of cells in the computer memory. Fetching an index is very efficient for retrieving items, adding items is sometimes difficult.

- Hash tables are 'dictionaries' or 'objects'. They are key pair value groupings and the main thing to worry about is key collisions. Very good for retrieving and adding.

- Stacks and Queues, LIFO stacks have push and pop and good for DFS (depth first search). FIFO have efficient add and remove with enqueue and dequeue but has limited uses.

- Graphs and Trees. graphs have nodes pointing to other nodes. The connections between them is the 'edge.' The tree has special rules, the binary search tree for example hs only 2 children per node. The left has to be less and the right has to be more. This allows searching to be very fast because you know where a value has to be. (as long as the tree is balanced!)

## [Basic Recursion](https://www.youtube.com/watch?v=vPEJSJMg4jY)

- Recursion is used to repeat a task until completion

- recursion calls the original function with updated arguments and returns when the task is finished! its very clean evn if its not the most performant way to do evvery task

- just like while loops, recursive functions have the potential to run forever. The recurive functioon has to have a built in stopper called the **base case** Otherwise the function terminates or returns!

## [Big O Notation](https://www.youtube.com/watch?v=v4cd1O4zkGw)

- **Big O** is about algorithmic efficiency. `O(1)` means the time is constant like a carrier pigeon which always delivers in the same amount of time. `O(n)` means the amount of data being transferred dictates the time it takes to transfer.

- The time it takes to run a function can be O(n^2^), to mow a square plot of land 100/100m can be O(a~rea~)

- To find the total runtime of multistep algorithms/functions would be O(a) + O(b) ... etc.

- an example of BigO for a nested array function i,j would be the time it takes to run through i times the time it takes to run through j: ~~O(n^2^)~~ => O(a\*b) ✓

- Rules for big O notation:

  - different steps get added

  - drop constants

  - different inputs = different variables

  - drop non-dominate terms

### [Big O cheatsheet](https://www.bigocheatsheet.com/

## Discussion Questions

- What is 1 of the more important things you should consider when deciding which data structure is best suited to solve a particular problem?
  - The time it would take to complete certain tasks and the scalability of the chosen structure

- How can we ensure that we’ll avoid an infinite recursive call stack?
  - be sure to add a base case that WILL be met

## Things I want to know more about

- deeper understanding of the linked lists, and with practice and use cases.
