# ♟️ Real-Time Multiplayer Chess Game

A web-based multiplayer chess game built using **Node.js**, **Express**, **Socket.IO**, and **chess.js**. The app supports two-player gameplay with real-time updates, drag-and-drop functionality, and spectator mode.

## 🌟 Features

- 🎮 Real-time two-player chess game
- 👤 Role assignment (white, black, spectator)
- 🧠 Legal move validation using [chess.js](https://github.com/jhlywa/chess.js)
- 🔁 Live move synchronization using Socket.IO
- 📦 Drag-and-drop UI for piece movement
- ♜ Board auto-rotates for the black player
- 👀 Spectators can watch the game in real time

## 🛠 Tech Stack

| Layer     | Technology               |
|-----------|---------------------------|
| Frontend  | HTML, CSS, Vanilla JS, EJS |
| Backend   | Node.js, Express          |
| Realtime  | Socket.IO                 |
| Game Logic| [chess.js](https://github.com/jhlywa/chess.js) |

## 🚀 Getting Started

### Prerequisites
- Node.js and npm installed

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/multiplayer-chess-game.git
cd multiplayer-chess-game

# Install dependencies
npm install

# Start the server
node app.js
