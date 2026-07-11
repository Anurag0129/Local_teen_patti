# Arc Tales Studio - Arena Hub

Welcome to the **Arena Hub**, a real-time, state-based interactive multiplayer strategy engine built with Node.js, Express, and Socket.io. The platform serves as an educational sandbox exploring synchronized state management, real-time client-server communication, and dynamic memory cache operations.

## 🚀 Features

- **Real-Time Multiplayer Node Allocation:** Dynamic seat allocation supporting up to 4 players simultaneously per network table segment.
- **Asynchronous State Synchronicity:** Optimized event-driven state transitions (Chaal, Pack, Show) utilizing a fast memory cache pipeline to eliminate latency blocks.
- **Connections Matrix & Verification:** Unique Player ID registration system allowing real-time searches, invitation handling, and instant peer-to-peer chat logs.
- **Masked Super Admin Console:** An exclusive administrative dashboard providing secure data surveillance, metrics monitoring, token adjustments, and profile management behind a double-locked authentication system.

## 🛠️ Tech Stack

- **Backend:** Node.js, Express Framework
- **Real-Time Layer:** Socket.io (WebSockets)
- **Database:** Local JSON File Registry System (`database.json`)
- **Frontend:** Vanilla JavaScript, HTML5 canvas templates, and custom Glassmorphism CSS layout grids.

---

## 💻 Getting Started (Local Development)

To run the application locally on your computer, follow these simple installation steps:

### Prerequisites
Make sure you have [Node.js](https://nodejs.org/) (v16 or higher) installed on your machine.

### Installation Steps

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/arc-tales-sandbox.git](https://github.com/YOUR_USERNAME/arc-tales-sandbox.git)
   cd arc-tales-sandbox

2. **Install Dependencies:**
   ```bash
   npm install

3. **Launch The Server:**
   ```bash
   node server.js

4. **Open in Browser:**
    Navigate to http://localhost:3000 inside your web browser. Open multiple tabs or different browser  windows to simulate multiple player segments!


# 🚀Free & Secure Cloud Deployment (Koyeb / Render)
This application is fully optimized for compliance filters on modern cloud environments.

# Recommended Hosting: Koyeb (Permanently Free)
1. Push your clean code repository to GitHub.

2. Log into the Koyeb Control Panel and select Create Web Service.

3. Authenticate with GitHub and select your repository segment.

4. Set the Health Check parameters: Change the protocol from TCP to HTTP and map the target path string to /.

5. Click Deploy. Koyeb will utilize the integrated Procfile configuration to route your application live on an automated public *.koyeb.app extension!

# 🛡️ Administrative Authentication Rules
The central system is double-locked behind hardcoded master configuration variables on the server layer. Access levels adjust dynamically upon matching:

    Master Identity Token: Configured inside server.js under ADMIN_EMAIL.

    Master Security Key: Configured inside server.js under ADMIN_MASTER_PASSWORD.

Note: For security compliance and phishing mitigation filters, all administrative log records are securely masked within the layout canvas (••••••).

# 📝 License
This project is developed strictly for educational sandbox prototyping and data analytics training exercises. Feel free to modify, expand, or fork the network matrix structures!

---

