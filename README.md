# Blog Website

## Overview
This project is a dynamic blog website built with Node.js, Express, MongoDB, and Mongoose. It allows users to create, read, update, and delete blog posts. The application features user authentication and association, ensuring that each blog post is tied to a specific user.

## Features
- **Create Blog Posts**: Users can create blog posts with a title, description, and image.
- **View All Blogs**: View a list of all blog posts, populated with user details.
- **Update Blogs**: Users can update their blog posts.
- **Delete Blogs**: Users can delete their own blog posts.
- **View Single Blog**: Fetch and display individual blog details.
- **User-Specific Blogs**: View all blog posts by a specific user.

## Technologies Used
- **Backend**:
  - Node.js
  - Express.js
  - MongoDB
  - Mongoose
- **Frontend**:
  - HTML
  - CSS
- **Other**:
  - Postman (for API testing)

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/blog-website.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd blog-website
    ```

3. **Install dependencies:**
    ```bash
    npm install
    ```

4. **Set up environment variables:**
    Create a `.env` file in the root directory and add the following:
    ```plaintext
    MONGO_URI=your_mongo_db_connection_string
    PORT=5000
    ```

5. **Run the application:**
    ```bash
    npm start
    ```

6. **Access the application:**
    Open your browser and go to `http://localhost:5000`

## API Endpoints

- **GET /api/blogs**: Get all blogs
- **POST /api/blogs**: Create a new blog
- **PUT /api/blogs/:id**: Update a blog by ID
- **DELETE /api/blogs/:id**: Delete a blog by ID
- **GET /api/blogs/:id**: Get a single blog by ID
- **GET /api/user-blogs/:id**: Get all blogs by a specific user

## Project Structure

├── models
│ ├── blogModel.js
│ └── userModel.js
├── controllers
│ ├── blogController.js
│ └── userController.js
├── routes
│ ├── blogRoutes.js
│ └── userRoutes.js
├── .env
├── app.js
├── package.json
└── README.md


## How to Contribute

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add new feature'`)
5. Push to the branch (`git push origin feature-branch`)
6. Open a pull request

7. 
**Happy Coding!** 🚀
