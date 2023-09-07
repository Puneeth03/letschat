# letschat - MERN chat app

![App Screenshot](screenshot.png)

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)

## Features

- **Authentication:** Users can sign up, log in, and log out securely.
- **One-on-One Chat:** Real-time messaging with other users.
- **Group Chat:** Create, join, and participate in group conversations.
- **User Addition/Deletion:** Add or remove users from group chats.
- **Profile Viewing:** View profiles of other users.
- **User Search:** Find users to start a new conversation.
- **Responsive Design:** Ensures a seamless experience on various devices.

## Technologies Used

- **Frontend:**
  - React
  - WebSocket (for real-time communication)

- **Backend:**
  - Node.js
  - Express.js
  - MongoDB
  - Socket.io (for real-time chat)

## Getting Started

To run this chat application locally, you'll need to set up both the server and client components. Follow these steps to get started:

### Prerequisites

Make sure you have the following software installed on your machine:

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)

### Installation

1. **Clone the Repository:**

   Start by cloning this repository to your local machine. Open your terminal/command prompt and run the following command:

   ```bash
   git clone https://github.com/Puneeth03/letschat.git
    ```
2. **Change to the Project Directory:**

    Navigate to the project directory:
    ```bash
    cd letschat
    ```
3. **Install Dependencies:**

    Install the required dependencies for both the server and the client:
    ```bash
    npm install
    ```
    ```bash
    cd frontend
    npm install
    ```
### Configuration:

  Before running the application, you may need to configure environment variables or set up a MongoDB database. Make sure to create a .env file in the server directory.
  The necessary env variable are port number, mongo_uri and jwt_secret.
  
  Running the Application:
  Now that you have the project set up, you can start the server and client to run the chat application locally:
  1. Start the Server:
     ```bash
     npm run start
     ```
     This will start the server on a specified port (e.g., http://localhost:5000).
  2. Start the Client:
     ```bash
     cd frontend
     npm start
     ```
     This will start the React development server and open the chat application in your default web browser.

### Usage:

  - Visit the application in your browser, sign up or log in, and start chatting with other users.
  - Explore the various features, such as one-on-one chat, group chat, user profiles, and more.
  - That's it! You've successfully set up and run the MERN Chat App locally. Enjoy chatting!
