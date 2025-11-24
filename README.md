# ⚡ Zenith | Focus & Achieve

<div align="center">
  <b>A Privacy-First Productivity Command Center</b>
  <br/>
  <br/>
  
  [![React](https://img.shields.io/badge/React-18-blue?style=for-the-badge&logo=react)](https://reactjs.org/)
  [![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.0-38bdf8?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)
  [![Node.js](https://img.shields.io/badge/Node.js-18-green?style=for-the-badge&logo=node.js)](https://nodejs.org/)
  [![MongoDB](https://img.shields.io/badge/MongoDB-Local-47A248?style=for-the-badge&logo=mongodb)](https://www.mongodb.com/)
</div>

<br/>

## 🌟 Overview

**Zenith** is a personal productivity app designed to run locally on your machine. It combines a beautiful "Glassmorphism" aesthetic with powerful focus features.

Unlike cloud apps that store your data on someone else's server, Zenith is designed to connect to your own local database. **You own your tasks, your data, and your focus.**

## ✨ Key Features

- **🎨 Zenith Ultra UI:** A stunning dark mode interface with animated backgrounds and frosted glass cards.
- **📅 Smart Calendar:** A custom-built interactive date picker to manage your schedule.
- **⚡ Focus Mode:** An immersive, full-screen timer with a kinetic ring to help you complete tasks.
- **✏️ Inline Editing:** Edit task details, dates, and priorities instantly without leaving the list.
- **🔒 Privacy Focused:** Runs 100% locally on your machine using your own database.

## 🚀 Getting Started

Follow these steps to get Zenith running on your computer.

### Prerequisites

1.  **Node.js:** [Download & Install](https://nodejs.org/)
2.  **MongoDB Compass:** [Download & Install](https://www.mongodb.com/try/download/compass) (This is your local database)
3.  **Git:** [Download & Install](https://git-scm.com/)

### 🔧 Installation

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/iamrishit8/my-todo-app-mern.git](https://github.com/iamrishit8/my-todo-app-mern.git)
    cd my-todo-app-mern
    ```

2.  **Install Dependencies**
    ```bash
    npm install
    ```

3.  **Configure Your Environment**
    Create a new file named `.env` in the root folder and paste this in:
    ```env
    PORT=3000
    MONGO_URI=mongodb://127.0.0.1:27017/zenith_db
    VITE_API_URL=http://localhost:3000/api
    ```
    *Note: This connects the app to your local MongoDB instance.*

4.  **Run the App**
    This command starts both the backend and frontend at the same time:
    ```bash
    npm run dev
    ```

5.  **Open Zenith**
    Visit `http://localhost:5173` in your browser.

---
<div align="center">
  Built with ❤️ by Rishit
</div>