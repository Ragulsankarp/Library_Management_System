📑:# Library_Management_System
This project is a simple implementation of a Library Management System using C++. It demonstrates basic Object-Oriented Programming (OOP) concepts such as classes, encapsulation, and access specifiers.

Below is an overview of its key features and components:

:accessibility::Features:                                 
1.Add Book: Allows users to add a new book to the library system. It prompts for ISBN, title, author, edition, and publication information.
2.Delete Book: Enables deletion of a book from the library based on ISBN. It shifts remaining books in the array to fill the gap.                        
3.Edit Book: Provides functionality to edit book details based on ISBN. Users can update any of the book's attributes.               
4.Search Book: Allows searching for a book by ISBN. If found, it displays all details of the book.                 
5.View All Books: Lists all books currently stored in the library, displaying their ISBN, title, author, edition, and publication details.                 
6.Quit: Terminates the program.             

Components:
Book Class: Defines a Book class with private attributes (isbn, title, author, edition, publication) and public methods (setIsbn, getTitle, etc.) for setting and getting book details.
Main Function: Handles the main menu and user input, directing control to appropriate functions based on user choices.
Functions: Separate functions (addBook, deleteBook, etc.) handle specific functionalities such as adding, deleting, editing, searching, and viewing books.
Counter Management: Uses a counter variable to manage the number of books stored in an array (books). Functions for incrementing and decrementing this counter ensure proper book management.
Additional Notes:
Input Handling: Utilizes getline for robust input handling, allowing spaces in book titles and other details.
Recursive main Call: While unconventional, the recursive call to main() after each operation ensures the program returns to the main menu, providing a continuous user interface.

Usage:
To run the program, compile the source code (library_management_system.cpp) using a C++ compiler and execute the resulting executable. Follow the prompts in the console to perform various library management operations.

This project serves as a foundational example of using OOP principles in a practical application and can be extended or modified for more complex library management scenarios.
