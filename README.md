# CReport

This repository contains the code for **CReport**, a crowdsourced anti-corruption and whistleblower platform. The project uses a **MERN** stack (MongoDB, Express, React, Node.js) organised as a simple monorepo with `client` and `server` folders.

## Folders

- `server` – Express REST API with JWT-based authentication.
- `client` – React application created with Vite.

## Getting Started

1. Copy `.env.example` to `.env` inside the `server` folder and provide values for the required environment variables. These include:
   - `MONGO_URI`
   - `JWT_SECRET`
   - `AES_KEY`
   The values should remain private and are **not** committed to version control.
2. From the `server` directory run:
   ```bash
   npm install
   npm start
   ```
3. From the `client` directory run:
   ```bash
   npm install
   npm run dev
   ```

The API will be available on `http://localhost:3000` and the React app on `http://localhost:5173` by default.
