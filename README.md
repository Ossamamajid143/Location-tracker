# Live Location Tracker

Live Location Tracker is a small Node.js application for displaying live GPS coordinates on a map in real time. It is useful for demos, educational projects, and location-based presentations.

## Features
- Real-time location updates using Socket.IO
- Map-based visualization of connected targets
- Simple login authentication
- Optional public tunnel support through cloudflared

## Requirements
- Node.js 16 or higher
- npm

## Installation
1. Clone the repository:
```bash
git clone https://github.com/madhanmaaz/live-location-tracker.git
cd live-location-tracker
```

2. Install dependencies:
```bash
npm install
```

3. Start the app:
```bash
npm start
```

4. Open the app in your browser:
```text
http://localhost:6589/login
```

## Default Login
```text
Username: admin
Password: admin
```

## Configuration
You can change the app port, login credentials, and auth token in [config.js](config.js).

## Project Structure
- [server.js](server.js) - Starts the Express server and Socket.IO
- [router.js](router.js) - Handles routes, authentication, and location updates
- [views/](views/) - HTML pages for login, home, map, and weather
- [public/](public/) - Static frontend assets

## Development
To run the app with automatic restarts during development:
```bash
npm run dev
```
