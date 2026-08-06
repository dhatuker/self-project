# Self-Project

A simple Express.js project.

## Project Structure

```
elf-project/
└── self-project/
    ├── index.js          # Main server file
    ├── package.json      # Project configuration
    ├── package-lock.json # Dependency lock file
    └── public/           # Static files
        └── index.html
```

## Installation

```bash
cd self-project
npm install
```

## Available Scripts

- `npm start` - Start the server
- `npm run dev` - Start the server with nodemon (auto-restart on changes)
- `npm test` - Run tests

## API Endpoints

- `GET /` - Returns welcome message
- `GET /health` - Health check endpoint
- `GET /api` - API info endpoint

## Running the Server

```bash
npm start
```

The server will run on http://localhost:3000 by default.