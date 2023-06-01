# Message Queues

## [Socket.io Chat Example](https://socket.io/get-started/chat/)

- Explain to a non-technical recruiter what the Chat Example (above) does.

The chat example app creates a server and gives the server a connection between the browser itself that will stay open and pass data in real time. The server uses this connection to send (serve) visual, message, and connection data (in the form of html and socket events) and then the browser makes that data look like a chat app (by pairing the data being fed by the server and the javascript that lives in the browser to add new html to the page which renders the events and messages in real time).

- What proof of life are we getting on the backend from the above app?

User connected and disconnected, socket ids

- Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?

socket.broadcast.emit() goes to everyone but the sender

## [Rooms](https://socket.io/docs/v4/rooms)

- What is a room and how might a room be useful?

A room is an arbitrary connection between a socket and the server. Technically its a server-side only connection. This connection is useful for grouping sockets and giving events to all of the sockets in a group and or further narrowing down the events.

- How do you join a room?

Subscribing to a room is done by emitting a join event to the server at a certain namespace

- how do you leave a room?

disconnect, timeout, otherwise, stop the connection

## [Namespaces](https://socket.io/docs/v4/namespaces/)

- What is a Namespace and what does it allow you to do?

A Namespace is a communication channel that allows you to split the logic of your application over a single shared connection (also called "multiplexing").

- Each namespace potentially has its own what?

Event Handlers, Rooms, and Middleware

- Discuss a possible use case for separate namespaces

separate namespaces allows you to create logic for different groups of users or separate out different parts of a service, and even provide an authenticated user route within the socket server.

### Reflection

super excited to make a proper chat app

## What I want to know more about

Socket middleware???????????????????
