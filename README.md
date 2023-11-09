# Live Chat Application

<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/10125/10125563.png" alt="App Logo" width="150">
</p>

> A real-time chat application built with React, Node.js, and Socket.io.


## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Folder Structure](#folder-structure)


## Overview

The **Live Chat Application** is a real-time messaging platform that allows users to communicate instantly with each other. It is built using modern web technologies, providing a seamless user experience. Users can register, log in, and start chatting with online friends, colleagues, or family members.

## Features

- **User Registration:** Create an account by providing a username, email, and password.

- **User Authentication:** Log in securely with your registered email and password.

- **Real-Time Messaging:** Instantly send and receive messages in real time.

- **Online Users:** See a list of users who are currently online and available for chatting.

- **Chat Notifications:** Receive notifications for new messages.

## Technologies Used

- **Frontend:** React, React Bootstrap
- **Backend:** Node.js, Express
- **Real-Time Messaging:** Socket.io
- **State Management:** React Context API
- **Styling:** CSS
- **Database:** MongoDB

## Prerequisites

- [Node.js and npm](https://nodejs.org/): Make sure you have Node.js and npm installed.

- [MongoDB](https://www.mongodb.com/): Install MongoDB locally or use a cloud-based MongoDB service.

## Getting Started

1. **Clone the repository:**
   ```sh
   git clone <repository-url>
2. **Navigate to the project directory:**
   ```sh
    cd live-chat-app
3. **Install server dependencies:**
   ```sh
    cd server
    npm install
4. **Install client dependencies:**
   ```sh
    cd client
    npm install
5. **Install socket dependencies:**
   ```sh
    cd socket
    npm install
6. **Create a .env file in the server directory with the following environment variables:**
   ```sh
    MONGODB_URI=<your-mongodb-connection-url>
    JWT_SECRET=<your-secret-key>
7. **Start the server:**
   ```sh
    npm start
8. **Start the client:**
   ```sh
    npm run dev
9. **Start the socket:**
   ```sh
    npm start

## Usage

- **Register or log in to your account.**

- **View the list of online users and start a chat by clicking on a user.**

- **Send and receive real-time messages.**


## Folder Structure

- client
  - public
  - src
    - assets
    - components
      - chat
    - context
    - hooks
    - pages
    - utils
- server
  - Controllers
  - Models
  - Routes
- socket

