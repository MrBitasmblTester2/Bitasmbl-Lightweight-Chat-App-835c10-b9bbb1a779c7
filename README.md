# Bitasmbl-Lightweight-Chat-App-835c10-b9bbb1a779c7

## Description
Build a web application that allows users to join anonymous chatrooms and exchange messages in real-time using WebSockets. The focus is on fast communication, simple interface, and responsive updates without requiring user registration.

## Tech Stack
- Express.js
- React
- Socket.IO

## Requirements
- Allow users to join chatrooms without authentication
- Send and receive messages in real-time using WebSockets
- Display messages with timestamps and user identifiers (anonymous)
- Handle multiple chatrooms simultaneously
- Gracefully handle disconnected users and reconnections

## Installation
bash
git clone https://github.com/MrBitasmblTester2/Bitasmbl-Lightweight-Chat-App-835c10-b9bbb1a779c7.git
cd Bitasmbl-Lightweight-Chat-App-835c10-b9bbb1a779c7
npm install


## Usage
bash
npm start


## Implementation Steps
1. Initialize Express.js server and integrate Socket.IO.
2. Implement chatroom handling for multiple rooms.
3. Broadcast and receive messages with timestamps and anonymous identifiers.
4. Manage user connections, disconnections, and reconnections.
5. Create React UI for joining rooms and viewing messages.
6. Connect React components to Socket.IO for real-time updates.