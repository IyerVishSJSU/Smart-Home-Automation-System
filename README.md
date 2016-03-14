# Smart-Home-Automation-System

TCP Client: This program is used to inject utilities utilization in the server required for monitoring. It also provides the option of generating reports which the client can use.

TCP Server: This program is used to accept request from clients. Receive utilization on a constant interval and store them in a file. Also construct a graph using GNU plot which is a functionality as a part of the graph report in the client.

How to compile the program
Extract the client to a directory and the server in another directory. Client 1 and 2 client ids are hardcoded in the program.

 Client1: Run the make file by going to the directly where tcpclient.c is present and type make in the command prompt.
 Client2: Run the make file by going to the directly where tcpclient.c is present and type make in the command prompt.
 Server: Run the make file by going to the directly where tcpserver.c is present and type make in the command prompt

How to run the program
 Open a terminal in Ubuntu and go to the directory that contains the output files created by make command.
 Once in the appropriate directory where the server is present, type in
	./tcpserver 8888 (port number on which the server will run)
 The $ prompt should now not be available meaning that the process is running.
 Open another terminal from which the client should be executed. Go to the same directory where the client is present and type in. (Client 1 and Client2)
	./tcpclient localhost 888
 Use the options provided by the client to invoke activities, which in turn invokes utilization.
 Client can also be used to generate a text or a graph report based on the utilities.
