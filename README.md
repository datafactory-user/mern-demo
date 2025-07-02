# MERN TODO Demo

This repository contains a minimal MERN (MongoDB, Express, React, Node) application that manages TODO entries.

## Structure

- **server** – Express API with MongoDB via Mongoose
- **client** – Simple React frontend using CDN scripts

## Running the Application

1. Install dependencies for the server:

```bash
cd server
npm install
```

2. (Optional) Install dependencies for the client to serve the static files:

```bash
cd ../client
npm install
```

3. Ensure MongoDB is running and accessible. Set `MONGODB_URI` if necessary.

4. Start the server:

```bash
cd ../server
npm start
```

5. In another terminal, serve the client:

```bash
cd ../client
npm start
```

The client will be available at `http://localhost:3000` (or the port `serve` reports) and the API at `http://localhost:5000`.
