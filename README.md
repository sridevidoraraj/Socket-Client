# Socket Programming

## Client Program

### Structure

This project structured using intellij platform and maven as build system.

#### About Project

-> This project is used for multiple clients can communicate simultaneously with one server.

-> Everytime server should get start first, then only client program should start.

-> In client program, server port number is given to communicate with server.

-> DataInputStream and outputStream are used to send and receive message from server.

-> If message from client send as "bye", then client will be terminated from server.

-> Multiple clients can communicate to server simultaneously, which client is sending message will get the reply from server simultaneously.

### Reference Link

[Link](http://net-informations.com/java/net/multithreaded.htm)

### To Run The Program
for maven, to build the project use
```
mvn clean install
```

to run the program, in main application by clicking the run button icon where the java class file is created.

```bash
Public class Client{
```
for multiple client run simultaneously, click on the run icon everytime to run the client program.








