# Blog API Project

This project is a simple Blog API built using Node.js, Express.js, and EJS templating. The application allows users to create, edit, delete, and retrieve blog posts. It also includes a user-friendly interface for managing posts.

---

## Features

- **Create New Blog Post**: Add a new blog post with a title, content, and author.
- **Edit Blog Post**: Update an existing blog post's title, content, or author.
- **Delete Blog Post**: Remove a specific blog post from the database.
- **View All Blog Posts**: Display all posts in a styled interface.
- **Responsive Design**: A clean and responsive user interface using CSS.
- **API Endpoints**:
  - `GET /get_post?id=<id>`: Retrieve a specific post by ID.
  - `POST /api/posts`: Create a new post.
  - `PATCH /edit/:id`: Update a specific parameter of a post.
  - `DELETE /api/posts/<id>`: Delete a post by ID.

---

## Technologies Used

- **Backend**:
  - Node.js
  - Express.js
- **Frontend**:
  - EJS (Embedded JavaScript Templates)
  - CSS for styling
- **Database**:
  - In-memory storage (e.g., `posts` array for simplicity)
- **Tools**:
  - Postman (for API testing)
  - Visual Studio Code

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/blog-api-project.git
   cd blog-api-project
