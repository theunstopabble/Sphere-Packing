# 💬 Mini WhatsApp Chats

<div align="center">

![GitHub repo size](https://img.shields.io/github/repo-size/Vikash-980/Mini-Whatsapp-Chats?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/Vikash-980/Mini-Whatsapp-Chats?style=for-the-badge)
![GitHub stars](https://img.shields.io/github/stars/Vikash-980/Mini-Whatsapp-Chats?style=for-the-badge&color=yellow)
![GitHub forks](https://img.shields.io/github/forks/Vikash-980/Mini-Whatsapp-Chats?style=for-the-badge&color=orange)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

<br />

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6b/WhatsApp.svg/512px-WhatsApp.svg.png" alt="WhatsApp Logo" width="100" height="100"/>

<h3 align="center">A Real-Time Chat Application</h3>

<p align="center">
  A lightweight, full-stack clone of WhatsApp Web featuring real-time messaging, user authentication, and a responsive UI.
  <br />
  <br />
  <a href="#-demo"><strong>View Demo</strong></a>
  ·
  <a href="https://github.com/Vikash-980/Mini-Whatsapp-Chats/issues"><strong>Report Bug</strong></a>
  ·
  <a href="https://github.com/Vikash-980/Mini-Whatsapp-Chats/issues"><strong>Request Feature</strong></a>
</p>

</div>

---

## 📋 Table of Contents

1. [🤖 About The Project](#-about-the-project)
2. [⚙️ Tech Stack](#-tech-stack)
3. [✨ Features](#-features)
4. [📸 Screenshots](#-screenshots)
5. [🚀 Getting Started](#-getting-started)
6. [🔐 Environment Variables](#-environment-variables)
7. [🤝 Contributing](#-contributing)
8. [📄 License](#-license)

---

## 🤖 About The Project

**Mini WhatsApp Chats** is a simplified version of WhatsApp built to understand the core concepts of real-time communication. It allows users to register, login, and chat instantly with friends without refreshing the page.

This project demonstrates the power of **WebSockets** combined with a robust **REST API**.

---

## ⚙️ Tech Stack

This project uses the MERN ecosystem:

| Component | Technology | Description |
| :--- | :--- | :--- |
| **Frontend** | ![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB) | User Interface (Hooks, Context API) |
| **Styling** | ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) | Modern Flexbox/Grid Layouts |
| **Backend** | ![NodeJS](https://img.shields.io/badge/Node.js-43853D?style=flat&logo=node.js&logoColor=white) | Server Runtime |
| **Framework** | ![ExpressJS](https://img.shields.io/badge/Express.js-404D59?style=flat) | API Routing & Middleware |
| **Database** | ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat&logo=mongodb&logoColor=white) | NoSQL Database for storing chats |
| **Real-time** | ![Socket.io](https://img.shields.io/badge/Socket.io-black?style=flat&logo=socket.io&badgeColor=010101) | Bidirectional event-based communication |

---

## ✨ Features

- 🟢 **Real-time Messaging**: Instant delivery of messages using Socket.io.
- 🔐 **Authentication**: Secure Login and Signup using JWT (JSON Web Tokens).
- 👤 **One-on-One Chat**: Private conversations between users.
- 📱 **Responsive Design**: optimized for Mobile and Desktop views.
- 💾 **Persistent Chat History**: Messages are stored in MongoDB and loaded on login.
- 🔔 **Online Status**: See when users are online (Real-time indicators).
- 🎨 **Modern UI**: Clean interface inspired by WhatsApp Web.

---

## 📸 Screenshots

<div align="center">
<!-- Replace these links with your actual screenshots -->
<img src="https://via.placeholder.com/800x400?text=Login+Screen" alt="Login Screen" width="80%" />
<br/><br/>
<img src="https://via.placeholder.com/800x400?text=Chat+Interface" alt="Chat Interface" width="80%" />
</div>

---

## 🚀 Getting Started

Follow these steps to set up the project locally.

### Prerequisites

*   **Node.js** (v14 or higher)
*   **MongoDB** (Local or Atlas URL)
*   **Git**

### Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/Vikash-980/Mini-Whatsapp-Chats.git
    cd Mini-Whatsapp-Chats
    ```

2.  **Server Setup (Backend)**
    ```bash
    cd server
    npm install
    ```

3.  **Client Setup (Frontend)**
    ```bash
    cd client
    npm install
    ```

### Running the App

1.  **Start the Backend Server**
    ```bash
    # Inside /server directory
    npm start
    # Server usually runs on port 5000 or 8000
    ```

2.  **Start the Frontend Client**
    ```bash
    # Inside /client directory
    npm start
    # Client usually runs on http://localhost:3000
    ```

---

## 🔐 Environment Variables

To run this project, you will need to add the following environment variables to your `.env` file in the **server** directory.

`server/.env`

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_super_secret_key
CLIENT_URL=http://localhost:3000
