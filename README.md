# Java-Projects

# Library Management System


<img width="374" alt="image" src="https://github.com/user-attachments/assets/be0e19f6-0d02-46ac-a8eb-637bdd8ca716" />

# Project Idea: "Library Management System"
This will be a Library Management System (LMS) where users can:
- Add new books.
- View a list of books.
- Edit or remove books.
- Search for books by title or author.
- Borrow and return books (keep track of availability).
- Store all book data in a file for persistence across program runs.
<img width="960" height="480" alt="image" src="https://github.com/user-attachments/assets/707bc5a0-c740-44de-8c91-b545de445559" />
<img width="1400" height="809" alt="image" src="https://github.com/user-attachments/assets/d4e47573-3454-4897-a5dc-dc9c918da020" />

<br/>

# Features of this Project:
- **Add a Book**: Users can add a new book with details like title, author, ISBN, genre, and availability.
- **View Books**: Display all the books with their details.
- **Edit Book**: Users can update book details.
- **Remove Book**: Delete a book from the system.
- **Search Books**: Search by title or author.
- **Borrow and Return Books**: Mark a book as borrowed or returned.
- **Data Persistence**: Save and load the books list from a file (books.txt) when the program starts.
- **Command-line interface (CLI)**: Interact with the system via console commands.

<br/>

# OOP Concepts Covered:
- **Classes and Objects**: For representing books, library operations, and the library itself.
- **Encapsulation**: Private fields with getters and setters for book attributes.
- **Inheritance**: (If you want to extend) You could extend functionality like having different types of books (e.g., textbooks, fiction).
- **Polymorphism**: In method overriding when editing or borrowing books.
- **File I/O**: For saving and reading data.


# Step-by-Step Breakdown:
- **Book.java**: Represents a book object.
    - Attributes: title, author, ISBN, genre, available (boolean).
    - Methods: Constructor, getters, setters, toString() for displaying.
- **Library.java**: Handles the collection of books and operations on them.
    - List of books (ArrayList<Book>).
    - Methods for adding, removing, updating, borrowing, and returning books.
- **LibraryApp.java**: Main program file with user interface (CLI).
    - Interacts with the Library class to perform operations.
    - Uses a loop to continuously offer the user options.
    - Accepts user input and calls appropriate methods.
- **BookFileHandler.java**: Handles file operations for saving/loading the list of books.
    - Saves the list of books to a file (books.txt).
    - Loads the list of books from the file.
