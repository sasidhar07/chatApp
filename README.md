# Chat Application

This is a simple chat application with functionalities for user registration, login, joining rooms, and real-time messaging.
# Here is working of app

## Features

- User Registration
- User Login
- Join Chat Room
- Real-time Messaging

## Technologies Used

- Frontend: HTML, CSS, JavaScript
- Backend: Node.js, Express
- Database: MongoDB (or any other preferred database)
- WebSocket: Socket.io (for real-time communication)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/sasidhar07/chat_app.git
    cd chat-application
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Set up the database:

    - Ensure you have MongoDB installed and running.
    - Create a `.env` file in the root directory with the following content (adjust the values as needed):

        ```env
        MONGO_URI=mongodb://localhost:27017/chat-app
        SECRET_KEY=your_secret_key
        ```

4. Run the application:

    ```bash
    npm start
    ```

    The application will be available at `http://localhost:3000`.

## Usage

### Register

1. Navigate to the registration page.
2. Enter your desired username and password.
3. Click on the "Register" button.

### Login

1. Navigate to the login page.
2. Enter your username and password.
3. Click on the "Login" button.

### Join a Chat Room

1. After logging in, you will be directed to the main chat interface.
2. Enter the name of the chat room you want to join.
3. Click on the "Join Room" button.

### Chat

1. Once inside a chat room, you can send messages in real-time.
2. Type your message in the input field and press "Enter" or click the "Send" button.

## Default Credentials

For testing purposes, you can use the following default user credentials:

- **Username:** Sasi
  - **Password:** sasi@123
- **Username:** Venkat
  - **Password:** venkat@123



