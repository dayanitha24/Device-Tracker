# 🚀 Real-Time Location Tracker


Location-Tracker.git'
## 📌 Overview

**Real-Time Location Tracker** is a web application designed to track and monitor locations dynamically.  
It uses **WebSockets (Socket.IO)** to stream location updates instantly and displays users’ positions on a live interactive map.  
All connected users can see everyone's location in real-time without refreshing the page.

---

## 🌟 Features

✔ Real-time location broadcasting using **Socket.IO**  
✔ **Interactive map** using **Leaflet.js & OpenStreetMap**  
✔ **Multi-user tracking** — every connected user visible live on the map  
✔ Lightweight & fast **Node.js Express server**  
✔ Supports both **web and mobile browser tracking**

---

## 🛠️ Tech Stack

| Component | Technology |
|----------|------------|
| Frontend | HTML, CSS, JavaScript |
| Backend | Node.js + Express.js |
| Real-time Communication | Socket.IO |
| Map | OpenStreetMap + Leaflet.js |

---

## 🔧 Installation & Setup

1️⃣ Clone the repository:
```bash
git clone https://github.com/dayanitha24/Location-Tracker.git
```
2️⃣ Navigate to the project directory:
``` bash
cd Location-Tracker
```
3️⃣ Install project dependencies:
``` bash
npm install
```
4️⃣ Start the server:
```bash
node app.js
```
5️⃣ Open your browser and navigate to:
``` bash
http://localhost:3000
```
🎯 How It Works

Clients send their live GPS coordinates via Socket.IO

The server broadcasts updates to all connected users

Leaflet.js updates each user's marker position instantly on the map
