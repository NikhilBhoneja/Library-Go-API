# Library-Go-API

This is a simple Go-based Library API for managing the borrowing and returning of books. The API provides endpoints for users to check out books, return them, and view the status of available books. It ensures proper tracking of borrowed books and prevents double-checking out of the same book.

# Features

Add books to library
Borrow books from the library
Return borrowed books
View status of available books

# Endpoints

GET /books - get Books
GET /books/:id Get book By Id
POST /books  create a Book
PATCH /checkout Borrow a book
PATCH /return - Return a book
