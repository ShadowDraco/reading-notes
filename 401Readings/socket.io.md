# Web Sockets and Socket.io

## Web Sockets

- What is a Web Socket?

A web socket is a computer communications protocol that provides duplex communications over a single TCP conntection.

- Describe the Web Socket request/response handshake and what happens once the connection is established.

The handshake is the process of using the http upgrade header to change from HTTP to WebSocket protocol.

- Web Sockets provide a standardized way for the server to send content to a client without first receiving a **request** from that client.

## Socket.io Tutorial

- What does the event handler io.on() do?

io.on listens for events and does a function with the socket that sent the event

- Describe some possible proof of life or proof that the code works as expected

When a io.on connection prints something to the console.

What does socket.emit() do?

socket.emit() sends a ping out to the websocket server so the event can be handled

## Socket.io vs Web Sockets

- What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).

webSocket is the base protocol established over tcp connection while socket.io is a library created to work with socket io and increase usability, reliability, and features.

- When would you use Socket.IO?

When you need need more control over what kind of events are being used and responded too, when you need fallbacks and more options

- When would you use WebSockets?

when you don't need all of that. but need less features, more memory, and more simplicity

## OSI Model Explained

- What are a couple of key takeaways from this video?

- The Open System Integration Model is a 7 layered model that shows the ways computers connect to each other. Each layer is a package of protocols that allow communication between systems and applications that do not speak the same languages.

## TCP Handshakes Explained

- Translate the gist of this video to a non-technical friend

- TCP stands for Transmission Control Protocol, Reliable and connection oriented Transport protocol. _Translation_: The TCP is a 'tunnel' that connects two computers who want to talk to each other. They exchange a secret 'handshake' inside this secure and safe tunnel and then give the all clear from both sides to exchange information.

## Things I want to know more about

well I just read practically everyone on the internet to do with sockets so how about more
