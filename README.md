**# Library Management System (Java)**

This project is a console-based library management system developed in Java for a university programming assignment. It models a small library environment and supports common library actions such as browsing the catalogue, borrowing and returning books, placing holds, and managing patrons.

The system uses a menu-driven command-line interface that allows users to search for books by author or genre, view all available titles, and access individual patron records. Patron records include currently borrowed books, borrowing history, and a calculated list of the patron’s three most frequently borrowed books.

The application is structured around separate classes with clearly defined responsibilities. The Library class manages program flow and user interaction, while the Catalogue class handles book availability, loans, and hold queues. Supporting classes such as Book, Author, Genre, and Patron represent core library entities and store related data. Equality is overridden in the Author and Genre classes to prevent duplicate entries and ensure consistent catalogue data.

An administrative mode allows authorised users to add or remove patrons and books from the catalogue. Java collections are used throughout the system to manage state, track borrowing history, and maintain hold queues.


**Features**

* Browse all books or only books currently available

* Search books by author or genre

* Borrow and return books

* Place holds with queue-based processing

* View patron records and favourite books

* Admin tools for managing patrons and catalogue entries

* This project was completed for university coursework and is intended for educational and portfolio use.
