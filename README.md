# MERN TODO Demo

This repository contains a minimal MERN (MongoDB, Express, React, Node) application that manages TODO entries.

## Structure

- **server** – Express API with MongoDB via Mongoose
- **client** – React frontend bundled with Webpack

## Running the Application

1. Install dependencies for the server:

```bash
cd server
npm install
```

2. Install dependencies for the client:

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

5. In another terminal, start the client using Webpack Dev Server:

```bash
cd ../client
npm start
```

The client will be available at `http://localhost:3000` (or the port `webpack-dev-server` reports) and the API at `http://localhost:5000`.
