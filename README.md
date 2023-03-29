# CS408_Computer-Networks
 A quiz game that is played over independent networks with multiple clients.
This trivia game is a term project for the course "CS408: Computer Networks" in Sabanci University.

The server takes questions from a text file with a correct answer. The answers must be integers. The server requires a port to function while the client executables requires a name, an existing IP address, and the server's port number to connect to the game. There is no maximum number of clients, but only one server can be connected to. If no clients can give a correct answer, the client that is the closest numerically wins the point. If it's a tie, the points are split.

# How to Use
To start a functioning game, first the server must be executed. The server executable is located in "CS408_Computer-Networks\server\server\bin\Debug" and it is the "server" executable (not to be confused with the XML Configuration File or the Program Debug Database inside the same folder). Only one server can be active for a game. After opening the file, the server requires you to input a port number and the number of questions the game will ask. The port number can be any integer (I recommend using "45" as the port number).

After the server is opened, the clients must be setup. The client executable is located in "CS408_Computer-Networks\client\client\bin\Debug" and it is the "client" executable (not to be confused with the XML Configuration File or the Program Debug Database inside the same folder). You can open as many clients as you want (as many "players" as you want). After opening the file, the client executable requires you to input the player's name, the IP address of your server, and your server's port.

For clients to connect to the server, the server must be started from the executable. After the server is active, the clients may connect to the server. When all the players are connected, the game can be started by the host.

If you require any more info about the project, please refer to the PDF file.