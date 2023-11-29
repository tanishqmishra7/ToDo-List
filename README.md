# ToDo-List
A simple to-do list application built with Go, leveraging Gorilla Mux for routing. This project aims to provide a lightweight and efficient solution for managing tasks

A simple to-do list application built with Go, leveraging Gorilla Mux for routing and SQLite for data storage. This project aims to provide a lightweight and efficient solution for managing tasks. Key features include:

CRUD Operations: Perform Create, Read, Update, and Delete operations on tasks.

RESTful API: Built with Gorilla Mux for handling HTTP requests.

Persistent Storage: Tasks are stored in an SQLite database, ensuring data persistence.

Technologies Used
Go: Programming language for backend development.
Gorilla Mux: Router for managing HTTP requests.
SQLite: Lightweight, serverless database for data storage.
How to Use
Clone the repository to your local machine.
Ensure you have Go and SQLite installed.
Run the application using go run main.go.
Open your browser and go to http://localhost:8080 to access the to-do list.
Project Structure
main.go: Main Go file containing the server logic.
handlers.go: HTTP request handlers using Gorilla Mux.
database.go: Database setup and interactions with SQLite.
views/: HTML templates for rendering the user interface.
