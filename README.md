# Chat Simple App

This is a simple, real-time chat application built with Node.js, Express, and Socket.io.

## Description

This application allows users to join a chatroom with a username and send messages to other users in real-time. It demonstrates the basic principles of building a chat application using WebSockets.

## Features

*   User-friendly interface to join a chatroom.
*   Real-time messaging between multiple users.
*   Notifications when a user joins or leaves the conversation.

## Technologies Used

*   **Backend:** Node.js, Express
*   **Real-time Communication:** Socket.io
*   **Frontend:** HTML, CSS, JavaScript

## Getting Started

### Prerequisites

*   Node.js and npm installed on your machine.

### Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/your-username/chat-simple-app.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd chat-simple-app
    ```
3.  Install the dependencies:
    ```bash
    npm install
    ```

### Running the application

1.  Start the server:
    ```bash
    node server.js
    ```
2.  Open your browser and go to `http://localhost:5000`.

## Project Structure

```
.
├── public/
│   ├── code.js         # Frontend JavaScript for chat functionality
│   ├── index.html      # Main HTML file for the chat interface
│   └── style.css       # CSS for styling the application
├── server.js           # Express server and Socket.io logic
├── package.json        # Project metadata and dependencies
└── package-lock.json