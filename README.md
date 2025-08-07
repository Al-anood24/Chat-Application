# Chat Application  
**Course:** Programming 2  
**Student:** Alanood Binlaksar  
**Date:** 7 August 2025  

## Description  
This is a basic terminal-based chat application written in Java using `Socket` and `ServerSocket`.  
It allows multiple users to join a chat room using separate terminal windows.  
Users can send and receive messages in real time.

---

## How to Run  

### 1. Compile the code  
Open your terminal and compile both files:

```bash
javac Server.java  
javac Client.java
```

### 2. Start the server  
In one terminal window, run the server:

```bash
java Server
```

### 3. Start the clients  
In separate terminal windows, run as many clients as you like:

```bash
java Client
```

---

## Features Implemented  
- Displays messages like: `User 2 has joined the chat.` or `User 3 has left the chat.`
- Each user message is tagged with their ID.  
  Example: `User 2: Hello everyone`
- Typing `exit` disconnects the client from the chat.
- The server shuts down automatically when all clients disconnect.
- Multithreading is used to handle multiple clients and broadcast messages.
- Code is clean and well-commented for better readability.
