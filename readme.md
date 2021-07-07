# Chat Server:

A generic server which enables communication via TCP, UDP and Broadcast protocols, and can
interpret customized protocols like chat between multiple users

--------------------------------------------------------------------------------
## Client Side:

#### Main:
* [ChatClient.java](https://github.com/itay-adi/ChatServer/blob/main/ChatClient.java): Conceptualize the client which connects to the server via TCP

#### Classes:
* [ChatMessageClient.java](https://github.com/itay-adi/ChatServer/blob/main/ChatMessageClient.java): Defining the ChatMessageClient class

--------------------------------------------------------------------------------

## Server Side:

#### Mains:
* [GenericServer.java](https://github.com/itay-adi/ChatServer/blob/main/GenericServer.java): Conceptualize the Server which the users can connect to

#### Classes:
* [ServerMessage.java](https://github.com/itay-adi/ChatServer/blob/main/ServerMessage.java): Defining the functionality of a Server Message

--------------------------------------------------------------------------------

## Tools:

* [ChatProtocol.java](https://github.com/itay-adi/ChatServer/blob/main/ChatProtocol.java): The chat protocol itself, which enables the user to: 
	* subscribe
	* send public message
	* disconnect

* [ChatMessage.java](https://github.com/itay-adi/ChatServer/blob/main/ChatMessage.java): Defining the ChatMessage class


----------------------------------

## Interfaces:

* [Connection.java](https://github.com/itay-adi/ChatServer/blob/main/Connection.java): An interface for the connection methods (init, stop and getId)
* [Message.java](https://github.com/itay-adi/ChatServer/blob/main/Message.java): An interface for the Messages (getKet and getData)
* [Protocol.java](https://github.com/itay-adi/ChatServer/blob/main/Protocol.java): An interface for the protocol itself, which contains message handler
* [ProtocolType.java](https://github.com/itay-adi/ChatServer/blob/main/ProtocolType.java): An interface which consists the customized protocols of the server
* [SendableConnection.java](https://github.com/itay-adi/ChatServer/blob/main/SendableConnection.java): An interface which consists the send/receive methods

----------------------------------

## Enums:

* [ChatMsgTypeServer.java](https://github.com/itay-adi/ChatServer/blob/main/ChatMsgTypeServer.java): An ENUM for the Chat Message Type from the Server
* [ChatMsgTypeUser.java](https://github.com/itay-adi/ChatServer/blob/main/ChatMsgTypeUser.java): An ENUM for the Chat Message Type from the Client
* [ConnectionType.java](https://github.com/itay-adi/ChatServer/blob/main/ConnectionType.java): An ENUM which consists the connection types: TCP, UDP, BC
