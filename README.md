# ChatWave

## Overview

ChatWave is a real-time chat application built using the MERN stack (MongoDB, Express, React, Node.js). This application allows users to communicate in real-time, supporting private messaging and user authentication.

## Features

- Real-time messaging using Socket.io
- User authentication with JWT (JSON Web Tokens)
- Responsive user interface
- Modular and scalable architecture

## Tech Stack

- **Front-End**:
  - React
  - Axios
  - React Router
- **Back-End**:
  - Node.js
  - Express.js
  - MongoDB
- **Real-Time Communication**:
  - Socket.io
- **State Management**:
  - Context API (or you can choose Redux)

## Installation

### Prerequisites

- Node.js (v14 or higher)
- MongoDB (local installation or MongoDB Atlas)
- npm (Node Package Manager)

### Clone the Repository

```bash
git clone https://github.com/your-username/ChatWave.git
cd ChatWave
```

### Back-End Setup

```bash
cd server
npm install
```

### Create a .env file in the server directory and add the following environment variables

```bash
MONGO_URI=<Your MongoDB Connection String>
JWT_SECRET=<Your JWT Secret>
```

### Front-End Setup

```bash
cd ../client
npm install
```

## Running the Project

```bash
cd ../
```

### Start the back-end server using nodemon

```bash
npm run server
```

### Start the Front-End Application

```bash
npm run client
```

### Start Both Servers Concurrently

```bash
npm run dev
```

## Usage

Open your web browser and go to http://localhost:3000 to access the application. Use the application to sign up and start chatting in real-time!
