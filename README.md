# Real-Time Chat Application

A modern real-time chat application built with WebSocket technology, enabling instant messaging capabilities across different chat rooms.

## 🚀 Tech Stack

### Frontend

- **React** - Built with React 18 using TypeScript
- **TailwindCSS** - For responsive and modern UI styling
- **WebSocket API** - For real-time bidirectional communication

### Backend

- **Node.js** with TypeScript
- **ws** library - For WebSocket server implementation
- **Room-based chat system** - Supporting multiple chat rooms

## ✨ Features

- Real-time messaging with WebSocket communication
- Room-based chat system
- Clean and modern UI with responsive design
- Dark mode support
- Type-safe implementation with TypeScript
- Scalable architecture supporting multiple concurrent users

## 🏗️ Architecture

The application follows a client-server architecture:

- Frontend connects to the WebSocket server on initialization
- Users can join specific rooms using room IDs
- Messages are broadcasted only to users within the same room
- Fully typed communication protocol between client and server

## 🛠️ Message Protocol

The application uses a JSON-based message protocol:
