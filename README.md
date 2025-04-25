# 💬 Chat Server using Websockets

## Overview

**Chat Server using Websockets** is a real-time chat application developed as a Computer Networking project. It utilizes WebSockets to enable instant communication between clients and the server. The application is built using Node.js, Express, and Socket.IO for the backend, with a simple HTML frontend interface.

## ✨ Features

* 🚀 **Real-Time Communication**: Enables instant messaging between connected clients
* 🔄 **WebSocket Integration**: Utilizes Socket.IO for efficient, bidirectional communication
* 🖥️ **Simple Frontend Interface**: Provides an easy-to-use HTML interface for users to send and receive messages

## 📁 Project Structure

```
Chat-Server/
├── index.html    # Frontend interface for the chat application
├── index.js      # Backend server setup using Node.js and Socket.IO
├── package.json  # Project metadata and dependencies
└── .gitignore    # Specifies files to be ignored by Git
```

## 📝 File Descriptions

* **index.html**: This file contains the frontend structure of the chat application. It includes the necessary HTML and JavaScript to establish a connection with the server and handle user interactions.

* **index.js**: This is the main server file. It sets up an Express server and integrates Socket.IO to handle WebSocket connections. The server listens for incoming client connections and facilitates message broadcasting between clients.

* **package.json**: This file contains metadata about the project, including dependencies like Express and Socket.IO, and scripts to run the server.

* **.gitignore**: Specifies files and directories that should be ignored by Git, such as `node_modules/` and other temporary files.

## 🚀 Getting Started

### Prerequisites

* Node.js installed on your machine.

### Installation

1. **Clone the repository:**

```bash
git clone https://github.com/fatima-amani/Chat-Server.git
cd Chat-Server
```

2. **Install dependencies:**

```bash
npm install
```

### Running the Application

1. **Start the server:**

```bash
node index.js
```

2. **Access the chat application:**
   Open your web browser and navigate to `http://localhost:3000`.

3. **Using the chat:**
   * Open multiple browser tabs or windows to simulate multiple clients.
   * Enter messages in the input field and observe real-time communication between clients.

## 🛠️ Technologies Used

* **Node.js**: JavaScript runtime environment.
* **Express**: Web framework for Node.js.
* **Socket.IO**: Library for real-time WebSocket communication.
* **HTML/CSS/JavaScript**: Frontend technologies for the user interface.

## 👩‍💻 Author

Fatima Amani  
GitHub: [@fatima-amani](https://github.com/fatima-amani)
