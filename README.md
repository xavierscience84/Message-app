# Chat Application

## Description
This project is a chat application that allows users to communicate in real-time. It integrates Firebase for authentication and real-time database operations.

## Features
- Real-time chat messages
- User authentication (signup, login, logout)
- Profile updates
- Media sharing capabilities

## Tech Stack
- React: For building the user interface
- Firebase:
  - Firestore: For database operations
  - Firebase Auth: For user authentication
  - Firebase Storage: For media uploads

## Project Structure
- `App.jsx`: Root component that handles routing.
- `ChatBox.jsx`: Component for displaying and sending messages.
- `LeftSidebar.jsx`: Sidebar component for navigation and user actions.
- `RightSidebar.jsx`: Displays user profile and media shared in chats.
- `firebase.js`: Configures Firebase services.
- `AppContext.jsx`: Manages global state using React Context.

## Setup and Installation
1. Clone the repository:
   ```bash
   git clone [repository-url]
