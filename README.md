# 🌍 GeoGO — Gather Together

GeoGO is a real-world multiplayer event map built with **Leaflet.js**, **PeerJS**, and the browser Geolocation API.

Players can create or join rooms, see each other live on a shared map, chat in real time, and hosts can pin community events such as:

- 🤝 Gather Here
- 🌱 Tree Planting
- 🧹 Clean-Up Drives
- 📦 Relief Operations
- 🏥 Medical Aid
- ✏️ Custom Events

Everything runs peer-to-peer with no backend required.

---

# ✨ Features

## 🗺️ Live Multiplayer Map
- Real-time GPS tracking
- Animated player markers
- Host crown indicator 👑
- Auto-sync positions between peers

## 💬 Live Chat
- Instant room chat
- Join/leave notifications
- Peer-to-peer messaging

## 📍 Event Pinning System
Hosts can:
- Pin events anywhere on the map
- Choose event categories
- Add custom descriptions
- Remove events live

## ⚡ Peer-to-Peer Networking
Powered by PeerJS:
- No dedicated server required
- Direct browser-to-browser communication
- Lightweight multiplayer architecture

## 🎨 Modern UI
- Responsive mobile-friendly interface
- Glassmorphism HUD
- Animated markers and notifications
- Smooth modal/event interactions

---

# 🧰 Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- Leaflet.js
- PeerJS
- OpenStreetMap
- Browser Geolocation API

---

# 🚀 Getting Started

## 1. Download the Project

Save the file as:

```bash
index.html
```

---

## 2. Run Locally

You can open it directly in your browser:

```bash
double click index.html
```

OR use a local server (recommended):

### VS Code Live Server
Install the Live Server extension and click:

```bash
Go Live
```

### Python Server

```bash
python -m http.server 8000
```

Then open:

```bash
http://localhost:8000
```

---

# 🎮 How to Use

## Create a Room
1. Enter your nickname
2. Click **Create**
3. Share the generated Room ID

## Join a Room
1. Enter your nickname
2. Enter the Room ID
3. Click **Join**

---

# 👑 Host Abilities

Hosts can:

- Pin event markers
- Remove events
- Sync state to newly joined players
- Manage the live room session

---

# 📍 Event Types

| Event | Icon |
|------|------|
| Gather Here | 🤝 |
| Tree Planting | 🌱 |
| Clean-Up Drive | 🧹 |
| Relief Ops | 📦 |
| Medical Aid | 🏥 |
| Custom Event | ✏️ |

---

# 📱 Mobile Support

GeoGO is optimized for:
- Android
- iPhone
- Tablets
- Desktop browsers

Works best with:
- Chrome
- Edge
- Safari
- Firefox

---

# 🔒 Permissions

GeoGO requires:

- 📍 Location access
- 🌐 Internet connection

Without GPS access, the app falls back to a default map location.

---

# 🧠 Architecture

GeoGO uses:

```text
Host Browser
   ↕
PeerJS Connections
   ↕
Player Browsers
```

The host acts as the synchronization relay for:
- Positions
- Chat messages
- Event pins
- Room state

---

# ⚠️ Limitations

- Requires internet connection
- PeerJS free signaling servers may occasionally disconnect
- Large rooms may impact performance
- GPS accuracy depends on device quality

---

# 🔮 Future Improvements

- User accounts
- Persistent rooms
- Event images
- Voice chat
- Route navigation
- Push notifications
- Firebase/WebSocket backend
- Event expiration timers

---

# 📸 Screenshots

Add screenshots here:

```markdown
![Menu](screenshots/menu.png)
![Map](screenshots/map.png)
![Events](screenshots/events.png)
```

---

# 📄 License

MIT License

Feel free to use, modify, and distribute.

---

# ❤️ Credits

Built using:
- Leaflet.js
- PeerJS
- OpenStreetMap Contributors

---

# 🌎 GeoGO

> “Gather together. Organize locally. Move in real time.”
