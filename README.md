# WebRTC Implementation with React, TypeScript, and Vite

This project is a WebRTC implementation that allows real-time communication between a sender and a receiver using WebSockets. The frontend is built with React and TypeScript, utilizing Vite for fast development and build processes. The backend is implemented using Node.js with the `ws` library for WebSocket communication.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Getting Started](#getting-started)
- [Frontend Setup](#frontend-setup)
- [Backend Setup](#backend-setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Real-time video streaming between sender and receiver.
- Type-safe implementation using TypeScript.
- Fast development with Vite's hot module replacement (HMR).
- ESLint configuration for code quality.

## Technologies

- **Frontend:**
  - React
  - TypeScript
  - Vite
  - ESLint

- **Backend:**
  - Node.js
  - WebSocket (`ws` library)

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the WebSocket server:
   ```bash
   node src/index.js
   ```

## Usage

- Open the frontend application in your browser (usually at `http://localhost:3000`).
- Click the "Send data" button to initiate the connection as a sender.
- Open another instance of the application to act as a receiver.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License.
