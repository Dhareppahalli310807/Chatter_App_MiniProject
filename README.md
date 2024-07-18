# Chatter App MiniProject

This project is a simple chat application that allows users to connect, join a chat room, and communicate in real-time. The application uses Node.js, Express, Socket.io, MongoDB, and Mongoose on the backend, and HTML, CSS, and JavaScript on the frontend.

## Features

- User can join the chat room with a username.
- Real-time messaging between connected users.
- Displays connected users in real-time.
- User typing notification.
- Stores messages and retrieves them when a new user joins.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm installed on your machine.
- MongoDB installed and running locally.

## Installation

# Clone the repository:

```sh
git clone https://github.com/Dhareppahalli310807/Chatter_App_MiniProject.git

1. Navigate to the project directory:
cd Chatter_App_MiniProject

2. Install the dependencies:
npm install

3. Configuration: The MongoDB connection string is hard-coded in the config.js file. Ensure MongoDB is running locally and the database name is chatterUp.

4. Start the server:
npm start

@ Usage
-- Join Chat Room: Enter a username to join the chat room.
-- Send Message: Type a message and press the send button.
-- Typing Notification: Displays a typing notification when a user is typing.
-- Connected Users: Displays the list of currently connected users.
-- Message History: Loads previous messages when a new user joins.

@ License
This project is licensed under the MIT License. See the LICENSE file for details.