# File Manager with Authentication, Pagination, and Background Processing

A simple and efficient file manager built with **Node.js**, designed to handle file uploads, secure user authentication, and task processing seamlessly.

---

## Features
- **Authentication**: Secure login and role-based access control using JWT.
- **File Management**: Upload, view, delete files with metadata stored in MongoDB.
- **Pagination**: Efficiently browse files with sorting and filtering.
- **Redis Integration**: Used for session management and caching frequently accessed data.
- **Background Processing**: Manage tasks like file compression or cleanup using worker threads or libraries like Bull.

---

## Tech Stack
- ![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white&style=for-the-badge) **Node.js**: Backend framework for handling requests and routing.
- ![Express.js](https://img.shields.io/badge/Express.js-000000?logo=express&logoColor=white&style=for-the-badge) **Express.js**: Lightweight server for RESTful APIs.
- ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white&style=for-the-badge) **MongoDB**: Database for storing file metadata and user information.
- ![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white&style=for-the-badge) **Redis**: In-memory data store for caching and sessions.
- ![JWT](https://img.shields.io/badge/JWT-000000?logo=jsonwebtokens&logoColor=white&style=for-the-badge) **JWT**: Secure authentication with JSON Web Tokens.
- ![Multer](https://img.shields.io/badge/Multer-FF5733?style=for-the-badge) **Multer**: Middleware for handling file uploads.
- ![Bull](https://img.shields.io/badge/Bull-EF4444?logo=redis&logoColor=white&style=for-the-badge) **Bull**: For managing background jobs.

---

## Installation and Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/elhaddoumi1999/alx-files_manager.git
   cd your-repo-name
