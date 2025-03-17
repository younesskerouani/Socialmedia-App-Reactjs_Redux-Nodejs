# E-commerce Website

A modern e-commerce platform with React.js frontend and Node.js backend.

## Live Demo

[View Live Demo](https://social-media-reactjs-front-end.vercel.app/)

<img width="958" alt="2" src="https://github.com/user-attachments/assets/221bca0b-dc44-4c11-9297-3cc0c057bc43" />

## Getting Started

Follow these simple steps to get the application running on your local machine.

### Prerequisites

- Node.js (v14 or higher)
- MongoDB
- npm or yarn

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/younesskerouani/Socialmedia-App-Reactjs_Redux-Nodejs.git
   cd ecommerce-website
   ```

2. Install and start the backend
   ```bash
   cd server
   npm install
   # Create a .env file with your MongoDB URI and other configs (see below)
   npm start
   ```

3. Install and start the frontend
   ```bash
   cd ../client
   npm install
   npm start
   ```

4. Open your browser and visit `http://localhost:3000`

### Backend Environment Variables (.env)
```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

## Features

User registration and authentication
Create, like, and comment on posts
Follow/unfollow other users
Real-time notifications
User profile customization

## Tech Stack

- **Frontend**: React.js, Redux, React Router
- **Backend**: Node.js, Express, MongoDB
- **Authentication**: JWT
