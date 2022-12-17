#Switter

Switter is a social networking application inspired by Twitter. It allows users to post messages (called sweets), follow and block other users, and view sweets from other users. The project is implemented using TCP sockets and has a graphical user interface (GUI) for users to interact with the server.

##Features
-Post messages (sweets) on the server using TCP sockets
-View all sweets from all other users except the requesting user
-Each sweet includes the username of the sweet owner, a unique sweet ID assigned by the server, and a timestamp of when the sweet was posted
-Connect to the server and enter a username to identify oneself using the GUI
-Follow and block other users using the GUI
-Delete sweets using the GUI

#Running the project
To run the project, you will need to start the server and then connect one or more clients to the server.

1. Compile the server and client project as a C# GUI application.
2.Start the server by specifying the port number it should listen on.
3.Connect a client to the server by specifying the server's IP address and port number using the GUI. You will also need to enter a username.
