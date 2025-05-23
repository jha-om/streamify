<h1 align="center">Fullstack Chat & Video Calling App</h1>

![Demo App](/frontend/public/chat.png)
---
## Architecture flow
![architecture_flow](https://github.com/user-attachments/assets/fdc9d744-47d4-4254-85b5-223d6467f7e5)
(ui/diagrams) => https://app.eraser.io/workspace/kiTRUaytr8fJjmfPj3PQ

(pending) => friends page and route...

## 🧪 .env Setup

### Backend (`/backend`)

```
PORT=5001
MONGO_URI=your_mongo_uri
STREAM_API_KEY=your_STREAM_API_KEY
STREAM_API_SECRET=your_STREAM_API_SECRET
JWT_SECRET_KEY=your_jwt_secret
NODE_ENV=development
```

### Frontend (`/frontend`)

```
VITE_STREAM_API_KEY=your_stream_api_key
```

---

## 🔧 Run the Backend

```bash
cd backend
npm install
npm run dev
```

## 💻 Run the Frontend

```bash
cd frontend
npm install
npm run dev
```
