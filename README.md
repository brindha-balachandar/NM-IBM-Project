💬 Chat Application UI

A simple Java-based Chat Application built using Swing for UI and Socket programming for communication.
This application allows real-time chatting between a server and a client — both implemented in a single Java file.


---

📘 Table of Contents

1. Overview


2. Features


3. Technologies Used


4. System Requirements


5. How It Works


6. Installation & Setup


7. Usage Instructions


8. Project Structure


9. Screenshots


10. Future Enhancements




---

🧩 Overview

The Chat Application UI provides a basic but functional two-way chat system using Java.
It demonstrates how client-server communication works through sockets, while maintaining an interactive and user-friendly interface using Swing components.

This project is ideal for students and developers learning about:

Java networking (Socket & ServerSocket)

GUI design with Swing

Threading for handling multiple operations simultaneously



---

✨ Features

✅ Single file app – works as both Server and Client
✅ Real-time messaging over local network
✅ Modern chat-style UI using Java Swing
✅ Multi-threaded – send & receive simultaneously
✅ Simple setup – no external libraries required
✅ Error handling and user prompts for connection setup


---

🛠️ Technologies Used

Component	Description

Java (JDK 8+)	Core programming language
Swing	GUI library for building interface
Sockets	For TCP/IP communication
Threads	To manage simultaneous send/receive actions



---

💻 System Requirements

Operating System: Windows / macOS / Linux

Java JDK: Version 8 or later

IDE (optional): IntelliJ IDEA, Eclipse, or VS Code



---

⚙️ How It Works

1. The program can act as either a Server or a Client.


2. The Server listens on port 5000 and waits for a client connection.


3. The Client connects to the server using the server’s IP address.


4. Both can send and receive messages simultaneously.


5. Messages are displayed in the chat window for easy communication.




---

🚀 Installation & Setup

1. Download or Clone the Project

git clone https://github.com/your-username/ChatApplicationUI.git
cd ChatApplicationUI


2. Compile the Java file

javac ChatApplication.java


3. Run the program

java ChatApplication




---

🧠 Usage Instructions

Step 1: Start as Server

Choose “Server” when prompted.

The application will start listening for a client connection.


Step 2: Start as Client

Run the same program again.

Choose “Client” when prompted.

Enter the Server IP Address (use 127.0.0.1 for same computer).


Step 3: Chat!

Type your message in the text field and click Send or press Enter.

Messages will appear on both ends in real time.



---

🗂️ Project Structure

ChatApplicationUI/
│
├── ChatApplication.java    # Main combined code (Server + Client)
├── README.md               # Project documentation
└── assets/                 # (Optional) screenshots or icons


---

🖼️ Screenshots

> 🪄 You can add your own screenshots in the assets folder and link them here.



Example:

Server Window	Client Window

	



---

🚧 Future Enhancements

🔹 Add multiple clients (group chat support)
🔹 Include user authentication/login
🔹 Add message timestamps
🔹 Store chat history in a database or file
🔹 Improve UI with modern styling (JavaFX versions)# NM-IBM-Project
