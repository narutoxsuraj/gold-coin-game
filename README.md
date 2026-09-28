# 🪙 Gold Mining

> A real-time 2-player number guessing game built with HTML, CSS, JavaScript and Firebase Realtime Database.

<p align="center">
  <strong>🎮 Play • Guess • Mine Gold • Win</strong>
</p>

## ✨ Overview

**Gold Mining** is a browser-based multiplayer game where two players compete by guessing each other's secret number.

Each player:
- chooses a secret number from **1–100**
- gets **5 guesses**
- earns a 🪙 coin when the opponent guesses their secret number
- keeps their secret hidden until the game ends

The game is designed with a dark blue, pink-neon gaming interface and real-time multiplayer synchronization.

## 🚀 Features

- 🌐 Real-time 2-player multiplayer
- 🔑 Room-code based matchmaking
- 👤 Clear Player 1 / Player 2 identity
- 🎯 Secret number guessing from 1–100
- 🪙 Hidden live coin scores
- 🔒 Secret numbers stay hidden during the match
- 🏆 Winner screen with animation
- 🎉 Celebration effects
- 🔄 Rematch / Play Again flow
- 📱 Responsive mobile-friendly UI
- 🌙 Premium dark neon gaming design
- 🔥 Firebase Realtime Database
- 🔐 Firebase Anonymous Authentication

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Game structure |
| CSS3 | UI, responsive design and animations |
| JavaScript | Game logic and interactions |
| Firebase Realtime Database | Real-time multiplayer state |
| Firebase Authentication | Anonymous player sessions |
| GitHub Pages | Web hosting |

## 🎮 How to Play

### Player 1
1. Open the game.
2. Enter your name.
3. Select **Online**.
4. Choose **Create Room**.
5. Share the generated room code with Player 2.

### Player 2
1. Open the game.
2. Enter your name.
3. Select **Online**.
4. Choose **Join Room**.
5. Enter Player 1's room code.

### Match
1. Both players choose a secret number.
2. Players take turns guessing.
3. A correct guess awards a coin to the **owner of the guessed secret number**.
4. The guesser does not immediately know whether the guess was correct.
5. After the allowed guesses are completed, the final result is revealed.

## 🌐 Live Demo

**GitHub Pages:**  
https://narutoxsuraj.github.io/gold-coin-game/

## 📁 Project Structure

```text
gold-coin-game/
├── index.html
└── README.md
```

The project is intentionally lightweight and can run directly from a static web host.

## 🔥 Firebase Setup

The multiplayer system uses Firebase Realtime Database.

For your own Firebase project:

1. Create a Firebase project.
2. Register a Web App.
3. Enable **Anonymous Authentication**.
4. Create a **Realtime Database**.
5. Add the Firebase configuration to `index.html`.
6. Configure database security rules before production deployment.

> Never place Firebase service-account credentials or private server keys in a frontend repository.

## 🔒 Security Note

The frontend Firebase configuration is intended for browser applications. Actual database access must still be protected with appropriate Firebase Security Rules.

For a production release, avoid leaving the database in open/test-mode rules.

## 📌 Roadmap

- [x] Premium game UI
- [x] Player identity
- [x] Room-based multiplayer
- [x] Real-time game state
- [x] Winner animation
- [x] Rematch flow
- [ ] Production Firebase security rules
- [ ] Game statistics
- [ ] Sound effects and additional feedback
- [ ] Android release
- [ ] Public leaderboard

## 👨‍💻 Author

**Suraj Kumar**

- GitHub: https://github.com/narutoxsuraj
- Project: https://github.com/narutoxsuraj/gold-coin-game

---

<p align="center">
  Made with ❤️ and JavaScript
</p>
