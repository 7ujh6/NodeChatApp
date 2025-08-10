# Real-Time Chat Application

### Project Overview

This is a full-stack, real-time chat application built to explore and master low-level, bidirectional communication between a server and multiple clients. This project was a practical exercise in building a Node.js backend with Express and integrating it with a frontend to create a dynamic, interactive user experience.

The core of this application is a Socket.io server that manages user connections, rooms, and message broadcasting, including profanity filtering.

### Core Features

*   **Real-Time Messaging:** Instantaneous, bidirectional communication between users in a chat room, powered by WebSockets via Socket.io.
*   **User & Room Management:** Simple and efficient handling of user joins, leaves, and message routing to specific rooms.
*   **Content Moderation:** Includes a basic profanity filter (`bad-words`) to demonstrate server-side message processing.

### Tech Stack

*   **Backend:** Node.js, Express.js
*   **Real-Time Communication:** Socket.io
*   **Development:** Concurrently, Nodemon

### Key Learning & Challenges

The primary goal of this project was to move beyond standard REST APIs and understand the event-driven architecture of a real-time system. I gained hands-on experience with WebSocket management, server-side event handling, and managing concurrent client connections. This project solidified my understanding of the foundational technologies that power modern collaborative applications.
