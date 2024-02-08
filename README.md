# Terminal Chat Server

A simple chat server implemented in C that runs on the terminal.

## Description

This server code allows multiple clients to connect and communicate with each other in a chat room environment. It uses TCP/IP sockets for communication.

## Getting Started

To set up and run the chat server on your local machine, follow these steps:

### Prerequisites

- Ensure you have a C compiler installed on your system.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/chat-server.git


### To run the server
1. Navigate to the project directory:

    ```bash
    cd server_eval

2. Compile the server code:
    ```bash
    gcc server_eval.c -o server

3. Run the compiled server binary:

    ```bash
    ./server

#### The server will start listening for incoming connections on port 3000.

### To run the client
1. Navigate to the project directory:

    ```bash
    cd client_eval

2. Compile the client code:
    ```bash
    gcc client_eval.c -o client

3. Run the compiled server binary:

    ```bash
    ./client


#### Clients can connect to the server using a chat client.

### Features
1. Listens for incoming connections from multiple clients.
2. Authenticates clients using a password.
3. Allows clients to send messages to each other in real-time.
4. Handles client disconnections gracefully.
