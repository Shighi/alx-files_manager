// README.md content
/*
# 0x04. Files manager

This project is a summary of this back-end trimester: authentication, NodeJS, MongoDB, Redis, pagination and background processing.

## Features

- User authentication via a token
- List all files
- Upload a new file
- Change permission of a file
- View a file
- Generate thumbnails for images

## Requirements

- Ubuntu 18.04 LTS using node (version 12.x.x)
- All files should end with a new line
- Code should use the js extension
- Code will be verified against lint using ESLint

## Installation

```bash
npm install
```

## Running the application

```bash
npm run start-server
```

## Running the worker

```bash
npm run start-worker
```

## Running tests

```bash
npm test
```

## Project Structure

```
.
├── controllers/
│   ├── AppController.js
│   ├── AuthController.js
│   ├── FilesController.js
│   └── UsersController.js
├── routes/
│   └── index.js
├── utils/
│   ├── db.js
│   ├── redis.js
│   └── queue.js
├── tests/
│   ├── redisClient.test.js
│   ├── dbClient.test.js
│   └── endpoints.test.js
├── server.js
├── worker.js
└── README.md
```

## API Endpoints

- `GET /status` - Check status of Redis and DB
- `GET /stats` - Get number of users and files
- `POST /users` - Create a new user
- `GET /connect` - Sign-in user and get token
- `GET /disconnect` - Sign-out user
- `GET /users/me` - Get current user info
- `POST /files` - Upload a new file
- `GET /files/:id` - Get file by ID
- `GET /files` - List files with pagination
- `PUT /files/:id/publish` - Make file public
- `PUT /files/:id/unpublish` - Make file private
- `GET /files/:id/data` - Get file content

## Environment Variables

- `PORT` - Server port (default: 5000)
- `DB_HOST` - MongoDB host (default: localhost)
- `DB_PORT` - MongoDB port (default: 27017)
- `DB_DATABASE` - Database name (default: files_manager)
- `FOLDER_PATH` - Files storage path (default: /tmp/files_manager)
*/
