# HTTPServer
This project hosts a HTTP server which can send files and respond with http messages.

## Description
This project is a way to host a server through Python's sockets. It currently hosts a game of 2048 written in JavaScript.
This program is also able to create HTTP messages depending on the the status of the server. This server is exapandable in the type of content that is possible to be hosted on this server. 

## Getting Started
### Dependencies
* Python >= 3.5

### How to Run
In the command line run the command 
```md 
python3 httpServer.py -p [PortNumber] -d [FileDirectory]
```
The deafult IP address is ``127.0.0.1``.
To use in a browser, type in the IP address followed by the port number followed by the file to access. 
For example: 
```md 
127.0.0.1:25565/index.html
```

