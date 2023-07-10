###  Socket.io

##### What is a Web Socket?
> WebSocket is a computer communications protocol, providing full-duplex communication channels over a single TCP connection

##### Describe the Web Socket request/response handshake and what happens once the connection is established.

>The handshake starts with an HTTP request/response, allowing servers to handle HTTP connections as well as WebSocket connections on the same port. Once the connection is established, communication switches to a bidirectional binary protocol which does not conform to the HTTP protocol.
##### standardized way for the server to send content to the client without being first requested by the client


#### Socket Tutorial

##### What does the event handler io.on() do?
> The on() function is used to listen for specific events from the clients. It takes two arguments: the event name and a callback function.




##### Describe some possible proof of life or proof that the code works as expected


* Unit Tests: Write tests to verify expected behavior and ensure the code produces correct output.
* Test Cases: Provide different inputs and verify expected outputs to validate code functionality.
* Console Logging: Use console.log to check code execution, variable states, and debug if needed.
* Code Review: Have another developer review the code for quality, correctness, and improvements.

##### What does socket.emit() do?


can create and fire custom events using the socket.emit function


##### What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).
**WebSocket** is the communication Protocol that provides bidirectional communication between the Client and the Server over a TCP connection.

**Socket.IO** is a library that enables real-time and full-duplex communication between the Client and the Web servers. 

##### When would you use Socket.IO?
* to handle all the degradation of your technical alternatives to get full-duplex communication in real-time.
* It also handles the various support level and the inconsistencies from the browser.
* It also gives the additional feature room support for basic publish infrastructure and thinks like automatic reconnect.
* Currently, AFAIK is the most used one and easier to help with vanilla web sockets.

#### When would you use WebSockets?
* It provides full-duplex communication, which helps in persisting the connection established between the Client and the Web Server.
* It also lives up to the standards and provides the accuracy and efficiency stream events to and from with negligible latency.
* WebSocket removes the overhead and reduce complexity.
* It makes real-time communication effortless and efficient.

##### What are a couple of key takeaways from this video?



1- OSI Model: The OSI model is a framework that standardizes network communication and is divided into seven layers.
2- Layered Structure: Each layer in the OSI model has specific functions and protocols.
3- Data Transfer: The OSI model guides the process of packaging and transmitting data between computers.


#### Translate the gist of this video to a non-technical friend

The TCP three-way handshake is a process that happens before data is sent over the internet using TCP. It's like introducing yourself before having a conversation.

Step 1: Your device asks the server, "Can we connect?"
Step 2: The server says, "Yes, let's connect!"
Step 3: Your device confirms, "Great, let's start talking!"

After this handshake, your device and the server can exchange information reliably and accurately. It's an important step in establishing a connection before data transfer begins.