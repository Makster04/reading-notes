# [Readings: Message Queues](https://github.com/codefellows/seattle-code-javascript-401d59/tree/main/class-13)

## [Socket.io](https://canvas.instructure.com/courses/8944808/discussion_topics/21361251)
1. **Explain to a non-technical recruiter what the Chat Example (above) does.** The Chat Example is a demonstration of real-time communication between users over the internet. It simulates a chat room where users can send and receive messages instantly without needing to refresh the page. This is achieved using Socket.IO, a library for real-time web applications, which enables bidirectional communication between the client (browser) and the server.
2. **What proof of life are we getting on the backend from the above app?** The proof of life on the backend from the above app would typically involve logging or console output to confirm that the server is running and is able to handle incoming connections from clients. This could include messages indicating when a new client connects or disconnects, when messages are received and sent, and any errors that occur during the process.
3. **Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?** Socket.IO gives us the io.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?
To send a message to everyone except for a certain emitting socket, you would use the broadcast flag with io.emit(). So the method call would be io.emit('event', data) with the broadcast flag: socket.broadcast.emit('event', data).

## [Rooms](https://socket.io/docs/v4/rooms)
1. **What is a room and how might a room be useful?** A room in Socket.IO is a virtual concept where sockets (clients) can join and leave dynamically. It allows for grouping sockets together, typically based on some common characteristic or purpose. Rooms are useful for organizing communication within a specific subset of connected clients, such as users in the same chat room or participants in the same game session.
2. **How do you join a room?** To join a room in Socket.IO, a client can use the join() method on the socket object provided by Socket.IO. For example, socket.join('roomName') will make the socket join the room named 'roomName'.
3. **How do you leave a room?** Leaving a room in Socket.IO is done using the leave() method on the socket object. For instance, socket.leave('roomName') will make the socket leave the room named 'roomName'.


## [Namespaces](https://canvas.instructure.com/courses/8944808/discussion_topics/21361251)
1. **What is a Namespace and what does it allow you to do?** A Namespace in Socket.IO is a way to segment the communication channels into separate namespaces. It allows you to create multiple communication channels on the same Socket.IO server, each with its own distinct name. This segmentation helps in organizing and managing different types of communication within a single application.

2. **Each namespace potentially has its own what? (hint: 3 things)** Each namespace potentially has its own event handlers, rooms, and configuration settings. This means that you can define specific logic for handling events, manage rooms independently, and configure settings such as authorization and logging on a per-namespace basis.
3. **Discuss a possible use case for separate namespaces** One possible use case for separate namespaces is in a multi-tenant application where different groups of users need to communicate separately. For example, in a chat application serving multiple organizations, each organization could have its own namespace. This allows for isolated communication channels, separate event handling logic, and customized configuration settings for each organization.

## Things I want to know

