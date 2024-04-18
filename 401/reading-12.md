# [Readings: Socket.io](https://github.com/codefellows/seattle-code-javascript-401d59/tree/main/class-11)

## [Web Sockets](https://en.wikipedia.org/wiki/WebSocket)
1. **What is a Web Socket?** A WebSocket is a communication protocol that provides full-duplex communication channels over a single, persistent TCP connection.
2. **Describe the Web Socket request/response handshake and what happens once the connection is established.** The WebSocket handshake begins with an HTTP request from the client to the server. Once the server accepts the request and establishes the WebSocket connection, both the client and server can exchange messages in both directions without the overhead of HTTP headers.
3. **Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.** Web Sockets provide a standardized way for the server to send content to a client without first receiving a request from that client.

## [Socket.io Tutorial](https://www.tutorialspoint.com/socket.io/)
1. **What does the event handler io.on() do?** The io.on() event handler in Socket.io is used to listen for incoming events from clients. It allows you to define functions to handle various events sent by clients.
2. **Describe some possible proof of life or proof that the code works as expected** You can demonstrate that the code works as expected by connecting multiple clients to the server and verifying that messages sent from one client are received by the others.
3. **What does socket.emit() do?** socket.emit() in Socket.io is used to emit events from the server to specific clients. It sends data to the client that triggered the event.

## [Socket.io vs Web Sockets](https://www.educba.com/websocket-vs-socket-io/)
1. **What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).** WebSocket is a protocol, while Socket.IO is a library that enables real-time, bidirectional communication between web clients and servers. Think of WebSocket as the underlying technology, and Socket.IO as a higher-level abstraction built on top of WebSocket, providing additional features and cross-browser compatibility.
2. **When would you use Socket.IO?** You would use Socket.IO when you need real-time, bidirectional communication between a web client and server and want features like automatic reconnection, broadcasting to multiple clients, and support for various transports (WebSocket, AJAX long polling, etc.).
3. **When would you use WebSockets?**  You would use raw WebSockets when you require a lower-level protocol for communication between clients and servers, without the additional features and abstractions provided by Socket.IO. This might be suitable for scenarios where you have specific performance or resource requirements and don't need the extra functionality provided by Socket.IO.

## [OSI Model Explained](https://www.youtube.com/watch?v=vv4y_uOneC0)
1. **What are a couple of key takeaways from this video?**
* > The OSI model breaks down network communication into seven layers, each responsible for specific functions.
* > Understanding the OSI model helps in troubleshooting network issues and designing network protocols and systems.

## [TCP Handshakes Explained](https://www.youtube.com/watch?v=xMtP5ZB3wSk)
2. **Translate the gist of this video to a non-technical friend** Imagine you want to have a conversation with someone over the phone. Before you start talking, you both need to ensure that you can hear each other clearly. The TCP handshake is like saying "Hello, can you hear me?" and waiting for a response to make sure the connection is good before you start exchanging information. Once both sides confirm they can hear each other, the conversation can begin smoothly.

## Bookmark and Review
* [Socket.io Documentation](https://socket.io/docs/v4/)
* [Socket.io Server API](https://socket.io/docs/v4/server-api)
* [Socket.io Client API](https://socket.io/docs/v4/client-api)
* [Socket Testing Tool](https://amritb.github.io/socketio-client-tool/)

## Reflection
1. **What are your learning goals after reading and reviewing the class [README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-12/)?** My learning goals post reviewing the Socket.io README include understanding OSI Networking Model layers, grasping TCP, UDP, and stateful networking concepts, implementing a Socket.io server for real-time messaging, and efficiently using events for message routing. Additionally, I aim to differentiate TCP and UDP usage and effectively utilize Socket.io's broadcasting capabilities for bidirectional client-server communication.
