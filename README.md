# Chat App

This project is a chat application developed using React for the front end and Node.js for the back end. The app allows users to create an account using Google Sign-In and enables them to chat with each other in real-time.

## Features

- **Google Sign-In**: Users can create an account and log in to the chat app using their Google credentials.
- **Real-Time Chat**: Once logged in, users can send and receive messages in real-time with other app users.
- **User Presence**: The app displays users' online/offline status to indicate their availability for a chat.
- **Message Notifications**: Users receive notifications for new messages when the app is not in focus or minimized.
- **User Profiles**: Users have customizable profiles with profile pictures and personal information.
- **Message History**: The app stores and displays the chat history for users, allowing them to view past conversations.

## Technologies Used

- **React**: A JavaScript library for building user interfaces.
- **Node.js**: A runtime environment for executing JavaScript code on the server side.
- **Socket.IO**: A library that enables real-time, bidirectional communication between web clients and servers.
- **Google Sign-In API**: Allows users to sign in using their Google credentials.
- **MongoDB**: A popular NoSQL database used for storing user information and chat history.

## Installation

To run the chat app locally, follow these steps:

1. Clone the repository:

   ```
   git clone https://github.com/garimadhiman/Chat-Application.git
   ```

2. Navigate to the project directory:

   ```
   cd Mern-Chat
   ```

3. Install the dependencies for both the frontend and backend:

   ```
   cd mern-chat-frontend
   npm install
   cd ../mern-chat-backend
   npm install
   ```

4. Set up Google Sign-In credentials:

   - Obtain a client ID from the Google Developer Console.
   - Add the client ID to the frontend configuration file: `frontend/src/config.js`.

5. Set up MongoDB:

   - Install MongoDB on your system if not already installed.
   - Create a new MongoDB database and note down the connection URI.
   - Add the connection URI to the backend configuration file: `backend/config.js`.

6. Start the development servers:

   ```
   cd mern-chat-frontend
   npm start
   ```

   ```
   cd mern-chat-backend
   npm start
   ```

7. Open your web browser and visit `http://localhost:3000` to access the chat app.

## Folder Structure

The project's folder structure is organized as follows:

```
Mern-Chat/
├── mern-chat-backend/
│   ├── models/
│   ├── node_modules/
│   ├── server.json
│   └── ...
├── mern-char-frontend/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── ...
└── README.md
```

- **frontend**: Contains the React frontend code for the chat app.
- **backend**: Contains the Node.js backend code for handling user authentication, chat functionality, and database operations.
- **README.md**: The file you are currently reading.

## Contributing

If you would like to contribute to this project, you can follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch with a descriptive name for your feature or bug fix.
3. Make your changes and test them thoroughly.
4. Commit your changes and push the branch to your forked repository.
5. Open a pull request on the original repository and provide a clear description of your changes.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- [React](https://reactjs.org/)
- [Node.js](https://nodejs.org/)
