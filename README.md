# TCP FILE SERVER PROGRAM
### Contributors - Nick Newlin
### Date started - 03/31/2024
## First Iteration - released 04/26/2024
#### - Contains two runnable classes, one for the server and one for the client.
#### - The main method in Server.java will initiate the startup sequence of the server, and will attempt to open a server socket on the port specified in the class's LISTENING_PORT field.
#### - The main method in Client.java will initiate the startup sequence of the client, and prompt the user for a command (upon startup, you should enter the "connect" command).
#### - This first iteration of this program is supposed to demonstrate my knowledge about how to implement multi-threading techniques while programming with java sockets
## Second Iteration - new features
#### - Rough implementation of a logging system (console and log file output)
#### - Created com.newlin.application package to store runnable classes for client and server
#### - Created com.newlin.util package to store utility classes
#### - Extracted runnable static inner classes into their own files
#### - Set up multithreading to manually start threads and also use an executor service as necessary
#### - Used synchronized code blocks to implement thread safety more effectively
#### - Added a FileNode object that builds a tree data structure representing the file system
#### - Changed Command and Response classes to be records
#### - Implemented the use of a config file to store application settings
## Second Iteration - backlog
#### - Configure Server and Client to use minimum number of threads for the thread pool
#### - Implement file system functionality
## Third Iteration - future plans
#### - Implement a GUI probably with Java Swing or JavaFX
#### - Provide documentation within source code
#### - Separate client and server programs into executable jar files
#### - Add code in the server startup that generates a log file that logs actions on the server
#### - Identify and label fatal exceptions, then initiate the graceful shutdown
#### - Add graceful shutdown for Client and Server