<h1 align="center"> iDiscuss Chat App - Javascript, Node.js & Socket.io🔥 </h1> 

# Sections 📚

✔️ Introduction
✔️ Technologies Used
✔️ Methodology
✔️ Screenshot of the Interface


# Introduction 📋

- The website is completely built on `Javascript` and `Node.js`.
- For the frontend I have used HTML and styled it using CSS.
- I have used `Socket.io` in this application for real time sending and receiving of messages.

This app is basically a whatsapp clone. A user enters the session by entering his/her name and he can communicate with people in that session. The app also notifies the other users when a new user has entered the chat room and alos when a user disconnects.

# Technologies used 🛠️
- Javascript
- Socket.io
- Node.js
- CSS
- HTML

# Methodology

Socket.IO is a library that enables low-latency, bidirectional and event-based communication between a client and a server.

It is built on top of the WebSocket protocol and provides additional guarantees like fallback to HTTP long-polling or automatic reconnection.

Socket.IO is composed of two parts:
A server that integrates with (or mounts on) the Node.JS HTTP Server socket.io
A client library that loads on the browser side socket.io-client
During development, socket.io serves the client automatically for us so we only install one module:
npm install socket.io
'socket.io'(http) creates a new socket.io instance attached to the http server. The io.on event handler handles connection, disconnection, etc., events in it, using the socket object.

We set up our server to log messages on connections and disconnections. And then we include the client script and initialize the socket object there, so that clients can establish connections when required.

# Screenshot of the Interface
<p align="center"> 
    <img src="images/interface.png" align="center" height="150"></img>
</p>
