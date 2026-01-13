# 🎰 Mini Casino Simulator

Welcome to **Mini Casino**, a full-stack web application featuring a suite of classic casino game simulators. This project is built for educational purposes and personal entertainment, showcasing modern web development techniques including RESTful APIs, real-time communication, and responsive UI design.

## ⚠️ IMPORTANT DISCLAIMER
**This is a simulator only.** 
* **NO REAL MONEY** is involved in any part of this application. 
* All currency is **VIRTUAL** and has no real-world value.
* This project was created for **educational purposes** to practice coding logic, database management, and UI/UX design.
* It is **nothing serious**—just a programming experiment and a fun way to learn how game mechanics work.

---

## 🚀 Features

### 🎮 Games
*   **One-Armed Joe Slots:** A stylish 3-reel slot machine with adjustable win probabilities, smooth CSS animations, and an "Autospin" mode.
*   **Neon Blackjack:** A classic 21 simulator featuring:
    *   Animated dealer card dealing.
    *   Hidden scores and dealer cards for maximum tension.
    *   An **AI Bot Hook** allowing you to implement your own blackjack strategies in JavaScript.
*   **Main Lobby:** A premium, responsive entry point with animated game cards.

### 🛠 Tech Stack (The Backend)
*   **Server:** Node.js with Express.
*   **Security:** JWT (JSON Web Tokens) stored in HttpOnly cookies and `bcrypt` for password hashing.
*   **Database:** SQLite3 for lightweight, file-based storage of user profiles and balances.
*   **Real-time:** Socket.io boilerplate included for future multiplayer expansions (Texas Hold'em/Global Blackjack).
*   **RESTful Design:** Clean API endpoints for Authentication, Profile Management, and Balance Updates.

---

## 🛠 Installation & Setup

1.  **Clone the project** to your local machine.
2.  **Install dependencies:**
    ```bash
    npm install
    ```
3.  **Start the server:**
    ```bash
    node server.js
    ```
4.  **Access the app:** Open your browser and go to `http://localhost:3000`.

---

## 📱 Responsiveness
The UI is designed to be fully responsive. Whether you are on a desktop or a smartphone, the game reels, cards, and buttons will scale appropriately to provide a "native app" feel.

---

## 🛡 License & Ethical Note
This project does not encourage or promote gambling. It is a logic-based simulation meant to demonstrate how to handle state, animations, and secure user sessions in a modern web environment.

**Please don't ban me. :)**