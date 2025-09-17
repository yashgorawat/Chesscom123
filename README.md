# ♟️ Online Multiplayer Chess (Chess.com Clone)

A full-stack real-time multiplayer chess application where two players can play from different browser tabs.  
Built with **React.js (frontend)**, **TypeScript + WebSockets (backend)**, and **chess.js (game logic)**.

---

## 🚀 Features
- Real-time two-player chess gameplay  
- Interactive chessboard UI with move highlighting  
- Turn-based game flow with legal move validation  
- Game termination states: check, checkmate, stalemate, draw  
- End-to-end data flow handling (player action → server → opponent’s UI)  

---

## 🛠️ Tech Stack
- **Frontend:** React.js, TailwindCSS
- **Backend:** TypeScript, Node.js, WebSockets  
- **Game Logic:** [chess.js](https://github.com/jhlywa/chess.js)  
- **Version Control:** Git, GitHub  

---

## 📂 Project Structure
chesscom123/
│── backend1/ # TypeScript server with WebSocket logic
│── frontend/ # React.js UI
│── README.md

---

## How to get started
-for backend
  cd backend
  npm install
  node dist/index.js

- for frontend
  cd frontend
  npm install
  npm run dev

---

## Play
Open two browser tabs

Each tab acts as a different player

Make your moves and enjoy real-time gameplay

##🎯 Learning Outcomes

Hands-on experience with full-stack development

Implemented real-time systems using WebSockets

Applied modular architecture for clean, maintainable code

Understood multiplayer game design & synchronization

##📸 Screenshots

<img width="1898" height="698" alt="image" src="https://github.com/user-attachments/assets/abbd86b0-0a60-4a22-992d-892fa1e18788" />
<img width="1898" height="651" alt="image" src="https://github.com/user-attachments/assets/bdbda204-3e69-4de8-ad49-5c3880786afb" />

##🔮 Future Improvements

Add player authentication & profiles

Implement a timer for competitive matches

Enable spectators to watch live games

Deploy frontend (Netlify/Vercel) & backend (Render/Heroku) for a live demo
