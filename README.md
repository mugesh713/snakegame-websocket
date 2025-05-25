
# 🐍 Live Multiplayer Snake Game

A real-time collaborative Snake game built with **HTML**, **CSS**, **JavaScript**, **WebSocket**, and **MongoDB**. This project enables **live multiplayer gameplay**, where players can join sessions, control their own snakes, and see others' moves in real time—powered by WebSocket-based communication.

## 🎮 Features

* 👥 **Multiplayer Support** – Multiple players can play simultaneously
* 🔄 **Real-Time Collaboration** – Instant movement and updates via WebSockets
* 🗃️ **Persistent Storage** – Player stats and sessions stored in MongoDB
* 💬 **Player Join/Leave Events** – Dynamic updates to the game state
* 🧱 **Collision & Scoring Logic** – Classic snake mechanics preserved for each player

---

## 🛠️ Tech Stack

* **Frontend**: HTML, CSS, JavaScript
* **Backend**: Node.js + WebSocket (Socket.IO or native WebSocket)
* **Database**: MongoDB

![Screenshot (355)_page-0001](https://github.com/user-attachments/assets/3ae00dd1-eca9-4866-b73b-c3c5c7720bd6)

## 🚀 Getting Started

1. Clone the repository:

```bash
git clone https://github.com/your-username/multiplayer-snake-game.git
```

2. Navigate to the project folder:

```bash
cd multiplayer-snake-game
```

3. Install server dependencies:

```bash
npm install
```

4. Start the WebSocket server:

```bash
node server.js
```

5. Open `index.html` in your browser (consider using Live Server or similar for local testing).

---

## 📡 WebSocket Flow

1. Client connects → server assigns player ID
2. Player input (arrow keys) → sent to server via WebSocket
3. Server processes logic, broadcasts updated game state
4. Clients render updated positions of all players' snakes

---

## 💡 Future Improvements

* 🧑‍🤝‍🧑 Private Rooms or Matchmaking
* 💬 In-Game Chat
* 📱 Mobile Optimization
* 🎨 UI/UX Enhancements

