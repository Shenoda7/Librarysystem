# Library System

This project is a simple **Library System** written in C++. It allows users to add books, search for books by prefix, track who borrowed which book, and manage the borrowing/returning of books. The system is designed to be an easy-to-use command-line interface for basic library operations.

## Features

- Add new books to the library
- Search for books by name prefix
- Print all books sorted by ID or name
- Track who borrowed each book
- Users can borrow and return books
- Print the list of users with their borrowed books

## Project Structure

The project uses two main data structures:
- **Books**: Stores book information such as ID, name, quantity, and total borrowed.
- **Users**: Stores user information including national ID, name, and borrowed books.

The system sorts books by ID or name and allows users to borrow or return books, keeping track of book availability and user borrowing history.

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/Shenoda7/librarysystem.git
    ```
2. Navigate to the project directory:
    ```bash
    cd librarysystem
    ```
3. Compile the code:
    ```bash
    g++ library_system.cpp -o library_system
    ```
4. Run the program:
    ```bash
    ./library_system
    ```

## Example

### Menu

- Add a book
- Search books by prefix
- Print who borrowed a book by name
- Print library by ID
- Print library by name
- Add a user
- User borrows a book
- User returns a book
- Print users
- Exit


### Sample Operations

- **Add a Book:**
Enter your book info: id & name & total quantity:

- **Search by Prefix:**
Enter book name prefix:

- **Borrow a Book:**
Enter user name and book name:


## Dependencies

- No external libraries required, only a C++ compiler like GCC or Clang.

## Project Inspiration

This project was inspired by a C++ course taught by **Mostafa Saad** and developed by **Shenoda Makram**.

