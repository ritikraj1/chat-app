# Real-Time Chat Application

Welcome to the Real-Time Chat Application! This web-based chat application allows users to join chat rooms, send messages, view active users, receive notifications for join/leave events, share real-time locations, and more.  
Hosted App URL- https://chat-app-zga4.onrender.com/

## Technologies Used

- Node.js
- Express.js
- Socket.io
- Mustache

## Features

- **Group Chatting**: Users can join chat rooms and participate in group chats.
- **Active Users List**: The chat window displays a list of active users in the room.
- **Join/Leave Notifications**: Users receive notifications when someone joins or leaves the chat room.
- **Message Timestamps**: Each message is accompanied by a timestamp and the username of the sender.
- **Automatic Scrolling**: Chat window automatically scrolls to display new messages.
- **Real-Time Location Sharing**: Users can share their real-time location with others in the chat room.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/chat-app.git
    ```

2. Navigate to the project directory:

    ```bash
    cd chat-app
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

## Usage

1. Start the server:

    ```bash
    npm start
    ```

2. Open a web browser and navigate to `http://localhost:3000`.

3. Enter a room number and provide a display name to join the chat room.

4. Start chatting with other users in the room!


## Code Structure

### index.js

This file contains the server-side code for handling socket connections, user management, message sending, location sharing, etc.

### messages.js

This module defines functions for generating message objects and location message objects.

### users.js

This module manages the users in the chat application, including adding, removing, and retrieving user data.

### chat.js

This file contains the client-side JavaScript code for interacting with the chat application, including sending messages, sharing locations, updating the UI, etc.


## Acknowledgements

- [Express.js](https://expressjs.com/)
- [Socket.io](https://socket.io/)
- [Mustache](https://github.com/janl/mustache.js/)

