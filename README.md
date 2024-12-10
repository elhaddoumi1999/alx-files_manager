# File Upload Platform - Backend

This is a simple backend platform for **file uploading and management** built with **Node.js**, **MongoDB**, **Redis**, and **JWT** authentication. The platform allows users to upload files, manage permissions, view files, and generate image thumbnails. Additionally, it supports background processing with **Bull** for handling tasks like generating thumbnails.

---

## Features
- **User Authentication** using JWT (JSON Web Tokens)
- **File Uploading**: Users can upload files.
- **File Permission Management**: Change the permission of files (public/private).
- **File Viewing**: Users can view their uploaded files.
- **Thumbnail Generation**: Automatically generate thumbnails for image files.
- **Pagination**: List files with pagination support.
- **Background Processing**: Image thumbnail generation is handled in the background using **Bull**.

---

## Tech Stack

![Node.js](https://img.icons8.com/color/48/000000/nodejs.png) **Node.js**: JavaScript runtime for building the backend API.  
![Express](https://img.icons8.com/color/48/000000/express.png) **Express.js**: Web framework for Node.js to handle routing and middleware.  
![MongoDB](https://img.icons8.com/ios-filled/50/000000/mongodb.png) **MongoDB**: NoSQL database for storing user and file data.  
![Redis](https://img.icons8.com/ios-filled/50/000000/redis.png) **Redis**: Temporary data storage (e.g., caching or session management).  
![JWT](https://img.icons8.com/ios-filled/50/000000/json-web-token.png) **JWT (JSON Web Tokens)**: Authentication mechanism for securely identifying users.  
![Multer](https://img.icons8.com/ios-filled/50/000000/multiple-files.png) **Multer**: Middleware for handling file uploads.  
![Sharp](https://img.icons8.com/ios-filled/50/000000/image.png) **Sharp**: Library for image processing, used to generate image thumbnails.  
![Bull](https://img.icons8.com/ios-filled/50/000000/queue.png) **Bull**: A robust queue system for background job processing.  
![Mocha](https://img.icons8.com/ios-filled/50/000000/test-tube.png) **Mocha**: Testing framework for writing and running tests.

---

## Requirements

Before running this project, ensure you have the following installed:

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/try/download/community) (or use a cloud service like [MongoDB Atlas](https://www.mongodb.com/cloud/atlas))
- [Redis](https://redis.io/download)
- [Postman](https://www.postman.com/) or any API client to test API requests.

---

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/elhaddoumi1999/alx-files_manager.git
   cd alx-files_manager
