# Hermoso Descanso

This project includes a hotel management frontend and backend prototype with MongoDB Atlas support.

## Setup

1. Copy `.env.example` to `.env`.
2. Update `MONGODB_URI` with your MongoDB Atlas connection string.
3. Run:
   ```bash
   npm install
   npm run start
   ```
4. Open `http://localhost:5000` in your browser.

## Features

- Express backend with authentication and API endpoints
- MongoDB Atlas cloud database support
- Simple React frontend served as static files
- Role-based views: admin, frontdesk, kitchen, housekeeping

## Available routes

- `POST /api/login`
- `GET /api/admin/dashboard`
- `GET /api/bookings`
- `GET /api/inventory/kitchen`
- `GET /api/rooms`
