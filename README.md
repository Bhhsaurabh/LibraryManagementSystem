# LibrayManagmentSystem
This project implements a simple Library Management System in C++. Features:  Add, search, issue, return, list, and delete books. File handling for persistent data storage. User-friendly command-line interface for interaction.Technologies Used: C++, file handling, object-oriented programming.

# Library Management System

## Project Overview
This project implements a simple Library Management System in C++. It allows librarians to manage books by performing operations such as adding new books, searching for books by title or ID, issuing and returning books, listing all books, and deleting books from the system. Data is stored persistently in a file (`library_data.txt`), ensuring that information is retained between sessions.

### Features
- Add new books with ID, title, and author.
- Search for books by title or ID.
- Issue books to mark them as issued.
- Return books to mark them as available.
- List all books in the library.
- Delete books from the system.

## Requirements
### Functional Requirements
- C++ compiler (e.g., g++) installed on your system.
- Ability to compile and run C++ programs from the command line.

### Non-Functional Requirements
- Basic understanding of C++ programming.
- Terminal or command prompt for executing the program.

## Instructions to Run
1. Clone the repository:
2. Navigate to the project directory:
3. Compile the program:
4. Run the executable:
5. Follow the on-screen instructions to interact with the Library Management System.

## Source Code
The source code (`LMS.cpp`) contains the implementation of the Library Management System. It includes classes for `Book` and `Library`, functions for managing books, and file handling for data persistence.

## Functions and Their Explanation
1. **addBook(Book book)**: Adds a new book to the library.
2. **searchBookByTitle(string title)**: Searches for a book by its title.
3. **searchBookById(int id)**: Searches for a book by its ID.
4. **issueBook(int id)**: Issues a book to mark it as issued.
5. **returnBook(int id)**: Returns a book to mark it as available.
6. **listAllBooks()**: Lists all books currently in the library.
7. **deleteBook(int id)**: Deletes a book from the library.
8. **loadFromFile(const string& filename)**: Loads book data from a file for persistent storage.
9. **saveToFile(const string& filename)**: Saves book data to a file for persistent storage.

## Contributing
Contributions are welcome! If you have suggestions or improvements, please fork the repository, create a new branch, and submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
