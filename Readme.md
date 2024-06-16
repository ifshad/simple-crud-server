

# User Management App - Server

This is the backend of the User Management Application built with Express and MongoDB. It provides RESTful APIs for user authentication and CRUD operations.

## Features

- User authentication with email and password
- RESTful API for user data
- CRUD operations for users

## Technologies Used

- Node.js
- Express
- MongoDB

## Prerequisites

Before you begin, ensure you have the following installed:

- Node.js (v14 or higher)
- npm or yarn
- MongoDB instance (local or cloud)

## Setup

### Clone the Repository

```bash
git clone https://github.com/ifshad/simple-crud-server
cd simple-crud-server
```

### Install Dependencies

```bash
npm install
```

### Configure Environment Variables

Create a .env file in the root of the backend directory and add your MongoDB connection string:
```bash
DB_USERNAME=your-db-username
DB_PASSWORD=your-db-password
```


### Start the Server

```bash
nodemon index.js
```