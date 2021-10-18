# Project
The librarian should be able to search for books by title to check their availability, check out available books, and return any books the members currently have. Details of all books in the library should be stored in an external text file. For each book the following information should be stored: ISBN, title, author, current loan status (is it available, and if not, who has it?), purchase date, and a unique ID number which can be used to identify different copies of the same book.

#Members
Members should be identified using their unique ID-numbers. For simplicity, I use 4-digit integers (e.g.: 1000-9999) for these IDs, and assume that all 4-digit numbers are valid members. (The program is able to distinguish between valid and invalid IDs, so that e.g. hh9# would not be accepted.

#SearchingForBooks
Program includes functionality to search for a book based on its title. Given a search term (e.g. Book_1), the program returns a complete list of books with that title and all their associated information.

#ReturningBooks
The librarian should be able to return books simply by providing the book's ID number. If the ID is invalid, or the book is already available, the program should return an error message. Otherwise, the text file should be updated accordingly.

#Weeding(Not Implemented)
Weeding is the systematic removal of books from a library based on selected criteria. The program should help users to find out which books need to be removed.  It will use the circulation criteria for the deselecting process (e.g. How long since it was last checked out?). There should be a log file (text file), which keeps the loan history of the books, to implement this functionality. The program must not have a functionality to remove book titles in the library system.
