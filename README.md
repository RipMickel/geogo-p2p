# GeoGO

Pokémon GO style realtime multiplayer GPS map using Leaflet.js, PeerJS, and GitHub Pages with no backend or database.

---

## Features

- Realtime GPS tracking
- Multiplayer live map
- Peer-to-peer networking
- No backend required
- No database required
- GitHub Pages deployable
- Mobile friendly
- Nickname login system
- Room creation and joining
- OpenStreetMap integration
- Lightweight and fast

---

## Tech Stack

- HTML5
- CSS3
- JavaScript
- Leaflet.js
- PeerJS
- WebRTC
- OpenStreetMap

---

## How It Works

GeoGO uses peer-to-peer communication with PeerJS and WebRTC.

One player creates a room and shares the Room ID.

Other players join using the same Room ID.

Players then share GPS coordinates directly with each other in realtime without needing a backend server or database.

---

## Demo Flow

1. Open the app
2. Enter nickname
3. Create or join a room
4. Allow GPS permissions
5. Start seeing nearby players on the map

---

## Deployment

This project is designed for GitHub Pages deployment.

### 1. Create a Repository

Example:

```bash
geogo-p2p
```

### 2. Upload Files

Upload:

```bash
index.html
```

### 3. Enable GitHub Pages

Go to:

```bash
Settings → Pages
```

Then:

```bash
Deploy from Branch → main
```

### 4. Open Your App

Example:

```bash
https://yourusername.github.io/geogo-p2p
```

---

## Project Structure

```bash
geogo-p2p/
│
├── index.html
├── README.md
├── assets/
├── styles/
└── scripts/
```

---

## Limitations

Because this project uses pure peer-to-peer networking:

- Host must stay online
- Best for small groups
- No permanent player storage
- No matchmaking server
- Some mobile networks may block WebRTC

---

## Recommended Future Features

- Animated avatars
- Collectible items
- Battle system
- Proximity radar
- Team system
- Voice chat
- AR mode
- Progressive Web App support
- Fog of war
- Nearby events

---

## Security Notes

This app uses browser geolocation.

Players must allow location permissions for the app to function correctly.

No location data is stored permanently.

---

## Dependencies

### Leaflet.js
https://leafletjs.com

### PeerJS
https://peerjs.com

### OpenStreetMap
https://www.openstreetmap.org

---

## License

MIT License

---

## Author

Built with ❤️ using WebRTC and GitHub Pages.
