# Chat Interface

This project is a real-time chat application that allows users to communicate with each other. The application also includes a speech-to-text feature for convenient message input.

## Technology Stack

### Frontend:

- **Vite + React**: For building the user interface.
- **React-Router**: For handling navigation within the application.
- **React-Redux/Toolkit**: For state management.
- **Tailwind CSS**: For styling the components.

### Backend:

- **Node.js**: For the server-side logic.
- **Express.js**: For handling HTTP requests and routing.
- **MongoDB**: For storing user data and chat messages.
- **Socket.IO**: For real-time communication between users.

## Running the Application

### Backend Setup:

1. Navigate to the backend directory: `cd backend`
2. Install dependencies: `npm install`
3. Start the server: `npm run dev`

### Frontend Setup:

1. Navigate to the frontend directory: `cd frontend`
2. Install dependencies: `npm install`
3. Run the development server: `npm run dev`
4. Access the application in your browser at `http://localhost:5173`

## Pages

### Login:

- Enter any username to login. If the username is not present in the database, a new account will be created automatically.

### Chat:

- **Sidebar**: Displays a list of all users.
- **Chat Area**: Allows users to send and receive messages in real-time.
- **Speech-to-Text**: Enables users to input messages using their voice.

## Features

### Real-Time Messaging:

- Utilizes Socket.IO for real-time communication between users.
- Messages are instantly delivered to the recipient.

### User Management:

- Automatically creates a new user account if the entered username is not found in the database.
- Displays a list of all users in the sidebar.

### Speech-to-Text:

- Allows users to input messages using their voice, enhancing accessibility and convenience.
