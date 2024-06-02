# Project: Book Management System (REST API with Spark)

## Project Explanation:
In this project, you will design a simple book management system using classes to represent individual books and a collection of books. Implement functionalities to add books to the collection, retrieve books, borrow books, and return books. Your program should provide the following functionalities:

- Add a Book to the Collection (api/v1/addBook)
- Retrieve Books from the Collection (api/v1/getBooks)
- getBooks can receive an optional parameter named isbn.
- Borrow a Book (api/v1/borrowBook)
- Return a Book (api/v1/returnBook)

## Implementation Details:
### Book Class:
Represents individual books.  
Fields: title, author, isbn, borrowed (boolean indicating if the book is borrowed).  
Constructor to initialize the book details.  
Methods to get and set the book details, including borrowing and returning the book.

### BookCollection Class:
Represents a collection of books.  
Contains methods to add a book, retrieve books, borrow a book, and return a book.  
Uses proper encapsulation to manage the book collection.

### REST API Endpoints:
- Add a Book (api/v1/addBook): Accepts book details (title, author, isbn) and adds the book to the collection.
- Retrieve Books (api/v1/getBooks): Returns a list of all books or a specific book if isbn is provided.
- Borrow a Book (api/v1/borrowBook): Accepts isbn and marks the book as borrowed if available. otherwise returns error.
- Return a Book (api/v1/returnBook): Accepts isbn and marks the book as returned if it was borrowed. otherwise it should report error.(Should not happen normally)
