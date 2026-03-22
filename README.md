💬 Client-Server Chat Application (Java)

📌 Description

This project is a Client-Server Chat Application built using Java.
It allows multiple clients to connect to a server and exchange messages in real-time.

The server handles multiple clients using multithreading, and messages sent by one client are broadcast to all connected clients.

---

🚀 Features

- 🔗 Multiple clients can connect to one server
- 💬 Real-time message communication
- 🔁 Message broadcasting to all clients
- ⚙️ Multithreading support
- 🖥️ Console-based application

---

🛠️ Technologies Used

- Java
- Socket Programming ("Socket", "ServerSocket")
- Multithreading
- Input/Output Streams

---

📂 Project Structure

ChatServer.java
ChatClient.java
README.md

---

🧠 Concepts Covered

- Client-Server Architecture
- Networking in Java
- Thread handling
- Communication using streams
- Real-time data exchange

---

▶️ How to Run

1. Compile both files

javac ChatServer.java
javac ChatClient.java

2. Run the server (first)

java ChatServer

3. Run clients (in multiple terminals)

java ChatClient

---

💡 How It Works

- The server starts and listens on a specific port
- Clients connect to the server using sockets
- Each client runs on a separate thread
- Messages sent by one client are received by all others

---

💬 Example Output

Server started...
New client connected

Client 1: Hello
Client 2: Hi!

---

⚠️ Notes

- Run the server before starting clients
- Use multiple terminals to simulate multiple users
- Make sure the port number is the same in both client and server

---

🌟 Future Enhancements

- Add usernames for clients
- Private messaging feature
- GUI using Java Swing / JavaFX
- Encryption for secure communication
- Chat history storage

---

👩‍💻 Author

Your Name
Deepthi

📜 License

This project is open-source and free to use for learning purposes.
