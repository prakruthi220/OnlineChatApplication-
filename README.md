# OnlineChatApplication-
A simple Java-based chat application using sockets and multithreading.

Structure
- `Server.java`: Starts the server and listens for client connections
- `Client.java`: Swing-based client interface
- `ClientHandler.java`: Handles individual client messages and broadcasts

How to Run
a.Server
1. Compile: `javac Server.java`
2. Run: `java Server`

b.Client
1. Compile: `javac Client.java`
2. Run: `java Client`
3. Enter the server IP when prompted

Note: Run the server before starting clients. Clients must connect to the server's IP on port `4444`.
