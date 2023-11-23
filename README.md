# Library-Management-System with oop principles


This project aims to develop a library management system that allows users to manage a collection of books and their availability status. The system provides functionalities for adding, borrowing, returning, and displaying books.

# oop design:
The game is designed using OOP principles.

The project consists of three main classes:
### Library Class:
#### The Library class is responsible for managing the collection of books and their availability status. It provides methods for:
       1-Adding Books: The addBook() method takes the title and author of a new book and creates a corresponding Book object, assigning it a unique ID and adding it to the library's list of books.
       2-Borrowing Books: The borrowBook() method takes the ID of the book to be borrowed and checks its availability. If the book is available, it marks it as borrowed and informs the user, otherwise it indicates that the book is unavailable.
       3-Returning Books: The returnBook() method takes the ID of the book to be returned and marks it as available if it is indeed borrowed.
       4-Displaying Books: The displayBooks() method iterates through the list of books and prints a summary of each book, including its ID, title, author, and availability status.
### Book Class:
#### The Book class represents a single book in the library. It maintains attributes for book information:
       1-bookId: Unique identifier for the book.
       2-title: Title of the book.
       3-author: Author of the book.
       4-isAvailable: Boolean flag indicating the book's availability status.
#### It also provides methods for accessing and modifying these attributes:
       1-getBookId(): Returns the bookId attribute.
       2-getTitle(): Returns the title attribute.
       3-getAuthor(): Returns the author attribute.
       4-isAvailable(): Returns the value of the isAvailable attribute.
       5-borrow(): Sets the isAvailable attribute to false, indicating that the book is borrowed.
       6-returnBook(): Sets the isAvailable attribute to true, indicating that the book is available.

### Main Class:
#### The Main class serves as the entry point for the application and handles user interactions. It creates an instance of the Library class and manages the main menu-driven interface:
       It creates a Scanner object to read user input.
       It displays the main menu and prompts the user to select an option.
       It processes the user's choice by calling the appropriate method of the Library class.
       It terminates the application when the user chooses the "Exit" option.

## User Interface:
users can select from the following options:

     1.Add Book: Add a new book to the library.
     2.Borrow Book: Borrow an available book from the library.
     3.Return Book: Return a borrowed book to the library.
     4.Display Books: Display the list of all books and their availability status.
     5.Exit: Terminate the application.

## To contribute:
If you would like to contribute to this project, please fork the repository and create a pull request. Please be sure to follow the coding style guide and test your changes before submitting them.


