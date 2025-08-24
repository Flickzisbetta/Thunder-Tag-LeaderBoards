# Leaderboard Website

## Features
- Submit scores and player names
- View top 10 players
- Simple REST API (Express + MongoDB)
- React frontend

## Usage

1. Run MongoDB locally or use MongoDB Atlas.
2. Start the backend:
    ```
    cd server
    npm install
    node index.js
    ```
3. Start the frontend:
    ```
    cd client
    npm install
    npm start
    ```
4. Open http://localhost:3000

## Customize
- To change the number of leaderboard entries, edit `.limit(10)` in `server/index.js`.