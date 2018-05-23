# ChatServerClient
One to One Simple Chat between Server and Client 
compile Servermsg.c on Server Node
gcc ServerMsg.c -o ServerMsg

Execute it:-

./ServerMsg 


gaurav@ubuntu:~$ ./ServerMsg 
Server got connection from client 192.168.56.141
Message received: Hey This is Client 

Reply to Client:
Hey This is Server
Message being sent to client: Hey This is Server




compile ClientMsg.c on Client Node

gcc ClientMsg.c -o ClientMsg 

Execute it :-

./ClientMsg 

gaurav@ubuntu:~$ ./ClientMsg 
Usage: client hostname
gaurav@ubuntu:~$ ./ClientMsg  192.168.56.142
Hey This is Client 
Message being sent: Hey This is Client 

Message received from Server is: Hey This is Server

Number of bytes received: 19




