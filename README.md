# 🚀 Xero 2.0

**Xero 2.0** is a powerful, modular, all-in-one Discord bot system built for flexibility, automation, and community management.  
This version brings a complete rewrite focused on speed, API integration, and control — both from Discord and the web dashboard.

---

## ✨ Features

### 🔧 Core System
- **Event Handler** – Automatically loads events from `/events`
- **Command Handler** – Supports both slash (`/`) and prefix commands
- **Database Integration** – Stores and syncs guild/user data
- **API System** – Allows other bots or services to fetch and execute commands
- **Utility Engine** – Includes tools for moderation, automation, and user interaction

---

### 🖥️ Dashboard
- Built-in **Express.js** dashboard for live control and ticket management  
- **HTML + EJS interface** for modern, fast UI  
- **Auto ticket logging** to `/logs/app/tickets`  
- Displays guild stats, command logs, and system info  

---

### 🧰 Utility Commands
- `/ping` – Check latency  
- `/userinfo` & `/serverinfo` – Advanced Discord info cards  
- `/say` – Send embedded messages  
- `/warn`, `/kick`, `/ban`, `/timeout` – Moderation suite  
- `/connect` – Secure DM contact between users and staff  
- `/ticket` – File-based ticket system with auto-save & close  

---

### 🧠 Developer Tools
- **Auto-deploy** and **auto-delete** scripts via `run.cmd`  
- **Command sync** between bots using the API  
- **JSON-driven randomizers** for custom response systems  
- **Custom logging** for activity, moderation, and errors  

---

## ⚙️ Setup

### 1️⃣ Clone the Repo
```bash
git clone https://github.com/YourName/Xero-2.0.git
cd Xero-2.0
