# Book Management REST API

A simple REST API built using Node.js and Express to manage a list of books.
The app performs full CRUD operations and stores data in-memory (no database).

## Features
Get all books
Create a new book
Update an existing book
Delete a book
In-memory storage
Easy to test using Postman

## Technologies Used
Node.js
Express.js
Postman (for API testing)

## Testing With Postman
Method	URL	Description
GET	/books	Fetch all books
POST	/books	Add new book
PUT	/books/:id	Update book by ID
DELETE	/books/:id	Delete book by ID
