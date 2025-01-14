# Stream Tube 

This application allows users to stream audio and video from their browser to a live platform (e.g., Youtube Live) using WebSockets and FFmpeg. The application is fully Dockerized for seamless deployment.

---

## Features

- **Frontend**: React-based user interface to capture and stream audio and video.
- **Backend**: Node.js server with Socket.IO for WebSocket communication and FFmpeg for live streaming.
- **Dockerized**: Both frontend and backend run in Docker containers.

---

## Requirements

- Docker and Docker Compose installed on your system.

---

## Getting Started

### 1. Clone the Repository

```bash
git clone <https://github.com/ankit0511/StreamTubeClone>
cd StreamTubeClone
/<repository_name>
  /client   # React frontend
  /index.js
  docker-compose.yml
# Build and start the containers
docker-compose up --build

# To stop the containers
docker-compose down


