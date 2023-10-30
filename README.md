# Chatroom

A real-time chatroom application built with Node.js, utilizing Express for the server framework and Socket.io for WebSocket communication.

## Features

- Real-time messaging
- Lightweight and fast
- Easy to deploy and customize

## Installation

Clone the repository:

```bash
# Install dependencies
npm install

# Start the application
npm start

# Build the Docker image
docker build -t chatroom .

# Run the Docker container
docker run -p 5000:5000 chatroom
