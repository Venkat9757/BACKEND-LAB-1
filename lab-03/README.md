# Lab 3: REST API, Query Parameters, Validation and Debugging

## Student Details
- Name: Venkatesh Kattempudi
- Registration Number: 252U1R9168
- Section: Gen Ai-S26
- Subject: Backend Development Fundamentals

## GitHub Repository
https://github.com/Venkat9757/BACKEND-LAB-1

## Objective
To develop a REST API for managing books using Node.js, Express.js and SQLite, including search, sorting, pagination, price filtering, validation and CRUD operations.

## Technologies Used
- Node.js
- Express.js
- SQLite
- better-sqlite3
- Postman

## Installation and Execution
1. Open the lab-03 folder in the terminal.
2. Install dependencies using: npm install
3. Start the server using: node server.js
4. Server URL: http://localhost:3000

The SQLite database is created automatically when the server starts.

## API Endpoints
| Method | Endpoint | Description |
|---|---|---|
| GET | /books | Get all books |
| GET | /books?search_q=Atomic | Search books by title |
| GET | /books?order_by=price&order=DESC | Sort books |
| GET | /books?limit=2&offset=0 | Paginate books |
| GET | /books?min_price=300&max_price=600 | Filter by price |
| GET | /books/:id | Get a book by ID |
| POST | /books | Add a book |
| PUT | /books/:id | Update a book |
| DELETE | /books/:id | Delete a book |

## Status Codes and Validation
- 200 OK: Successful retrieval, update or deletion.
- 201 Created: Book successfully added.
- 400 Bad Request: Invalid input or query parameter.
- 404 Not Found: Requested book does not exist.

## Screenshots
### 01. Get All Books
![Get All Books](screenshots/01-get-all-books.png)

### 02. Search Books
![Search Books](screenshots/02-search-books.png)

### 03. Sorting
![Sorting](screenshots/03-sorting.png)

### 04. Pagination
![Pagination](screenshots/04-pagination.png)

### 05. Price Filter
![Price Filter](screenshots/05-price-filter.png)

### 06. Get Book by ID
![Get Book by ID](screenshots/06-get-book-by-id.png)

### 07. POST Success
![POST Success](screenshots/07-post-success.png)

### 08. POST Validation Error
![POST Validation Error](screenshots/08-post-validation-error.png)

### 09. PUT Success
![PUT Success](screenshots/09-put-success.png)

### 10. DELETE Success
![DELETE Success](screenshots/10-delete-success.png)

### 11. Not Found Error
![Not Found Error](screenshots/11-not-found-error.png)

### 12. Query Validation
![Query Validation](screenshots/12-query-validation.png)

## Result
The REST API was implemented and tested using Postman. Search, sorting, pagination, price filtering, CRUD operations and validation responses were tested.
