#Library Management App

This project is a simple library management web application that allows users to manage a collection of books. Users can add new books, view the list of books, toggle the read status of books, and remove books from the library. The app is built using HTML, CSS, and JavaScript.


#Features

Add New Books: Input book details through a form and add them to the library.

View Library: Display all books in a table or card format.

Unique Identifier for Each Book: Each book has a unique ID generated using crypto.randomUUID().

Toggle Read Status: Change the read status of books directly on their display card or table row.

Remove Books: Delete books from the library with a single click.


#Usage

Add a New Book.

Click the "New Book" button to bring up the form.

Fill in the book's title, author, number of pages, and read status.

Submit the form to add the book to your library.

View and Manage Books

All books will be displayed in the library table or as cards.

Use the toggle button to change the read status of a book

Click the "Remove" button to delete a book from the library.


#Implementation Details

Book Constructor

Defines the blueprint for creating book objects, including attributes like title, author, pages, and read status.

Library Array

Stores all book objects, serving as the data source for the app.

Unique IDs

Each book is assigned a unique ID using crypto.randomUUID() for reliable tracking.

Event Handling

Utilizes event.preventDefault() to manage form submissions without refreshing the page.

DOM Manipulation

Dynamically updates the display to reflect changes in the library array
