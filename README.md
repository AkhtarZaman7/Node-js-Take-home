# Blog Platform RESTful API - Take-Home Assignment

Welcome to your take-home assignment for the Node.js Engineer position. This document provides a comprehensive overview of the assignment, including setup instructions, API endpoint details, and submission guidelines. Your task is to create a RESTful API for a blogging platform, demonstrating your expertise with Node.js, data modeling, authentication, and API development.

## Objective

Build a RESTful API for a blogging platform that supports user management, blog post operations, and comments, incorporating JWT-based authentication and adhering to best practices in security and code quality.

## Requirements

### API Endpoints

- **User Management**: Implement CRUD operations for user profiles.
- **Authentication**: Secure the API using JWT-based authentication.
- **Blog Posts**: Allow authenticated users to perform CRUD operations on blog posts.
- **Comments**: Enable CRUD operations for comments on blog posts; restrict deletion and updating to the creator of the comment.

### Data Modeling

- Design schemas for users, blog posts, and comments using MongoDB and Mongoose. Consider attributes like user roles, timestamps, and relationships between collections.

### Security

- Implement security measures such as password hashing, input validation, and protection against common web vulnerabilities.

### Testing

- Write comprehensive unit and integration tests for your API endpoints.

### Documentation

- Provide clear API documentation and setup instructions in this README.

## Tech Stack

- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Testing Framework**: Jest or Mocha (optional)
- **Documentation**: Swagger or Postman (for API documentation)

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
