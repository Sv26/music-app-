# Spotify Clone

This project is a clone of Spotify, built using Node.js for the backend, React for the frontend, and MongoDB for the database. The application allows users to explore music, create playlists, and manage their account.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
- [Project Structure](#project-structure)
- [Scripts](#scripts)
- [License](#license)

## Features

- User authentication (sign up, log in, log out)
- Explore and search for songs
- Create, edit, and delete playlists
- Play and pause music tracks
- Responsive design

## Tech Stack

### Frontend:
- **React**: A JavaScript library for building user interfaces.
- **Redux**: A state management library.
- **Tailwind CSS**: A utility-first CSS framework.
- **React Router**: For client-side routing.
- **React Toastify**: For toast notifications.

### Backend:
- **Node.js**: JavaScript runtime built on Chrome's V8 JavaScript engine.
- **Express.js**: A minimal and flexible Node.js web application framework.
- **MongoDB**: NoSQL database for storing user data, playlists, and songs.
- **JWT (JSON Web Token)**: For secure user authentication.
- **Bcrypt.js**: For hashing user passwords.

## Getting Started

### Prerequisites

Make sure you have the following installed on your system:

- **Node.js** (v14.x or higher)
- **npm** or **yarn**
- **MongoDB** (running locally or accessible via a cloud service like MongoDB Atlas)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/spotify-clone.git
   cd spotify-clone
## Install backend dependencies:
cd backend
npm install

## Install frontend dependencies

cd frontend
npm install

## .env

PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret


## Start the backend server:

cd backend
npm run dev

## Start the frontend server

cd frontend
npm run dev


