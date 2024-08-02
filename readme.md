# 📚 Library Management System

Welcome to the Library Management System! This application allows admins to manage the library's book inventory and members to borrow and return books. The system supports multiple users with different roles (Admin and Member).

## Features ✨

### User Roles

- **Admin** 🛠️: Has the authority to add and remove books from the library.
- **Member** 👥: Can borrow and return books from the library.

### Admin Features

- **Add Book** ➕: Add new books to the library with details like title, author, and genre.
- **Remove Book** ❌: Remove books from the library using their book ID.
- **Display All Books** 📖: View a list of all books in the library.
- **Display Available Books** 📚: View a list of books that are currently available for borrowing.

### Member Features

- **Borrow Book** 📥: Borrow a book from the library using its book ID.
- **Return Book** 📤: Return a borrowed book to the library.
- **Display All Books** 📖: View a list of all books in the library.
- **Display Available Books** 📚: View a list of books that are currently available for borrowing.
- **Display My Borrowed Books** 📑: View a list of books borrowed by the member.

## Getting Started 🚀

### Prerequisites 📋

Ensure you have a C++ compiler installed on your system.



## Usage 🛠️

1. **Login** 🔐: Use the pre-registered users ("Admin" and "User") for testing or register new users.
2. **Select User Type** 👤: Choose whether you want to log in as an Admin or a Member.
3. **Admin Actions**:
    - Add a book by entering its title, author, and genre.
    - Remove a book by entering its ID.
    - View all books or only the available ones.
4. **Member Actions**:
    - Borrow a book by entering its ID.
    - Return a borrowed book by entering its ID.
    - View all books, available books, or the books you have borrowed.

## Code Structure 🗂️

- **User Class** 👤: Base class for Admin and Member.
- **Admin Class** 🛠️: Derived class with additional functionalities for managing books.
- **Member Class** 👥: Derived class with functionalities for borrowing and returning books.
- **Book Class** 📚: Represents a book with details like ID, title, author, genre, and status (borrowed/available).
- **Library Class** 🏛️: Manages the collection of books and users, handles book borrowing and returning, and user registration.

## Example Usage 📖

- **Login as Admin** 🛠️:
    - Username: Admin
    - Password: admin@example.com
- **Login as Member** 👥:
    - Username: User
    - Password: user@example.com

Upon logging in, follow the menu options to perform actions specific to your role.

## Future Improvements 🚀

- **User Authentication** 🔐: Implement password protection for users.
- **Enhanced Book Search** 🔍: Allow searching for books by title, author, or genre.
- **User Interface** 🖥️: Develop a graphical user interface for easier interaction.

## Contribution 🤝

Feel free to contribute to this project by submitting pull requests. Please ensure your changes are well-documented and tested.

## License 📜

This project is licensed under the MIT License.

---

Happy coding! 😊 If you have any questions or feedback, feel free to reach out.

