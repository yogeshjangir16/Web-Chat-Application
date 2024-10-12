# Real Time Chat Application
This application is built using Socket.IO, Node.js, HTML, and CSS.

## Features

- **Real-time messaging**: Communicate with others in real-time.
- **Speech recognition for message input**: Use voice commands to send messages (browser support required).
- **Simple and intuitive user interface**: Clean and easy to use.

## Installation

### Prerequisites

Ensure that you have the following installed on your system:

- [Node.js](https://nodejs.org/) (which includes npm, Node Package Manager)
  
### Running Locally

#### 1. Clone the repository:

```bash
git clone https://github.com/yogeshjangir16/Web-Chat-Application.git
cd Web-Chat-Application
```

#### 2. Open the project folder in VS Code.
#### 3. Install dependencies:
```bash
npm install
npm install socket.io
npm install -g nodemon
```
#### 4. Start the application:
Navigate to the nodeserver directory and run the server using Nodemon:
```bash
cd nodeserver
nodemon index.js
```
#### 5. Open the HTML file:

To open the client-side of the application, follow these steps:

1. Right-click on the `index.html` file.
2. Select "Open with Live Server" (ensure you have the Live Server extension installed in Visual Studio Code).
3. The application will now be accessible at [http://localhost:8000](http://localhost:8000).

## Usage

### Microphone Access

To use the speech recognition feature for message input, allow microphone access when prompted by your browser. This will enable you to send messages using your voice.

### How it Works

#### Socket Communication

This application leverages Socket.IO to establish real-time, bidirectional communication between the client and the server. Here’s a brief overview:

1. The client connects to the server through a socket.
2. Once connected, both the client and server can emit and listen to specific events.
3. This allows for instant message transmission and reception, enabling real-time communication between users.

### Enjoy Chatting!

Feel free to explore the application and start chatting in real time. If you encounter any issues or have suggestions for improvements, please open an issue on the [GitHub repository](https://github.com/yogeshjangir16/Web-Chat-Application/issues).


