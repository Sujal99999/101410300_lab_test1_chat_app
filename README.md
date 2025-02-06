# Chat Application

## Overview

This is a real-time chat application where users can:

- Sign up and log in to their accounts.
- Join different chat rooms.
- Send and receive messages in real-time.
- View chat history for each room.
- See typing indicators when another user is typing.
- Messages sent in one room are isolated and not visible in other rooms.

The application uses **Socket.io** for real-time communication and **MongoDB** for storing user and chat data.

---

## Features

1. **Sign Up and Login**:

   - Users can create an account using the sign-up page.
   - The login page authenticates the user and redirects them to the chat interface.

2. **Real-Time Chat**:

   - Users can join different chat rooms like DevOps, Cloud Computing, Sports, or Node.js.
   - Messages sent in a room are visible only within that room.

3. **Typing Indicator**:

   - A notification shows when a user is typing in a room.
   - This enhances the user experience by mimicking real-world chat applications.

4. **User Isolation in Rooms**:

   - Each room has a unique context. Messages sent in one room will not interfere with another.

5. **Logout**:
   - Users can log out, which clears their session data.

---

## Technologies Used

1. **Frontend**:

   - HTML, CSS, JavaScript, and Bootstrap for styling.
   - LocalStorage for user session management.

2. **Backend**:

   - Node.js with Express for API and server.
   - MongoDB with Mongoose for database operations.
   - Socket.io for real-time communication.

3. **Database**:
   - MongoDB Atlas is used for storing user credentials and chat messages.

---

## How to Run the Application

1. Clone the repository:
   ```bash
   git clone https://github.com/Hemin7776/101396990_lab_test1_chat_app.git
   cd 101396990_lab_test1_chat_app
   ```
