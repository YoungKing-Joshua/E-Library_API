# E(Electronic) Library API
This project is an API for managing a library of books. It's built using the Nest.js framework and Mongoose for MongoDB integration.

## Features

- Get a list of books with optional filtering by genre.
- Add a new book to the library.
- Retrieve information about a specific book by ID.
- Edit the details of an existing book.
- Mark a book as read or unread.
- Delete a book from the library.

## Getting Started

### Prerequisites

- Node.js (version X or above)
- MongoDB server running (locally or remote)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/YoungKing-Joshua/E-Library_API.git
   ```

2. Navigate to the project directory:

   ```bash
   cd E-Library_API
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Set up the database connection:

   Create a `.env` file in the root directory and provide your MongoDB connection string:

   ```env
   MONGODB_URI=mongodb://localhost:27017/libraryApp
   ```

5. Start the server:

   ```bash
   npm start
   ```

The server will start running at `http://localhost:3001`.

## Usage

You can interact with the API using tools like `curl`, Postman, or any HTTP client. Alternatively, you can develop a front-end application that consumes the API.

## API Endpoints

- **GET** `/api/book`: Get a list of books.
- **GET** `/api/book/:bookId`: Get information about a specific book.
- **POST** `/api/book`: Add a new book to the library.
- **PUT** `/api/book/:bookId`: Edit the details of a book.
- **PATCH** `/api/book/:bookId`: Update specific details of a book.
- **DELETE** `/api/book/:bookId`: Delete a book from the library.

For detailed request and response information, refer to the [API documentation](API_DOCUMENTATION.md).