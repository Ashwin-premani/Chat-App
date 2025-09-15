# Chat-App

A simple, real-time chat application built by **Ashwin Premani**.

---

## 📌 Table of Contents
- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Requirements](#requirements)
- [Installation](#installation)
- [Running](#running)
- [Configuration](#configuration)
- [Project Structure](#project-structure)
- [Contact](#contact)

---

## About
Chat-App is a lightweight project to demonstrate real-time messaging in the browser.  
It can be extended with authentication, rooms, or persistent storage.

---

## Features
- 📡 Real-time messaging with WebSockets / Socket.IO  
- 🎨 Clean, minimal UI (HTML/CSS/JS)  
- 🔧 Easily extensible backend  
- 📱 Responsive layout (if styled)

---

## Tech Stack
| Layer      | Technology |
|------------|------------|
| Frontend   | HTML, CSS, JavaScript |
| Backend    | Node.js, Express |
| Real-Time  | Socket.IO |
| Database   | *(optional)* MongoDB / SQLite |

---

## Requirements
- [Node.js](https://nodejs.org) (v14+)
- npm or yarn

---

## Installation
```bash
# Clone the repository
git clone https://github.com/Ashwin-premani/Chat-App.git
cd Chat-App

# Install dependencies
npm install
# or
yarn install
```
## Running
```bash
npm start
# or
node server.js
```
Then open:
```bash
http://localhost:3000

```

If the repo is static-only, you can run:
```bash
npx http-server . -p 8080
```
## Configuration
Create a `.env` file if you need custom settings:

```env
PORT=3000
MONGO_URI=mongodb://localhost:27017/chatapp
SESSION_SECRET=replace_with_a_secret
```
Markdown

## Configuration
Create a `.env` file if you need custom settings:

```env
PORT=3000
MONGO_URI=mongodb://localhost:27017/chatapp
SESSION_SECRET=replace_with_a_secret
```
## Project Structure
```bash
Chat-App/
├─ server.js
├─ package.json
├─ public/
│  ├─ index.html
│  ├─ css/
│  │  └─ styles.css
│  └─ js/
│     └─ main.js
└─ README.md

```
## Contact
### Ashwin Premani

📧 ashwinpremani1@gmail.com

🌐 GitHub: @Ashwin-premani
