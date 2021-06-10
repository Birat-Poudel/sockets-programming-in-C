### Socket Programming in C

## Sockets:
1. Sockets are the basic building block of network communication.
2. Sockets are the low level endpoint used for processing information across a network.
3. Common networking protocols like HTTP, and FTP rely on sockets underneath to make connections.
4. Sockets sit underneath of all the common internet protocols that we use.
5. HTTP is build upon existing TCP protocol.

## "Client" Socket Workflow:
socket() => connect() => recv()

## "Server" Socket Workflow:
socket() => bind() => listen() =>accept() => send()/receive()

bind() : It is used to the bind that socket with an IP and Port.