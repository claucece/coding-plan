# Tarea 2: Biblioteca

Duración: una semana aproximandamente.

## Business Case

The Bangalore Public Library has approached us to design and implement a Library
Management System for them. Based on their requirements, we have decided to develop
a new system named Biblioteca. Since the library has a large list of requirements,
we will be making multiple releases of Biblioteca, with each release incrementally
adding more functionality.

In order to easily add more functionality in the future as well as maintain a
high level of quality, Biblioteca will be built using a test driven approach.

## User Stories

* Welcome Message - As a customer, I would like to see a welcome message when
I start the application, so that I feel welcome and know that Biblioteca is available.

* List Books - As a customer, after the welcome message appears I would like to
see a list of all library books, so that I can browse for books I might want to
check-out. Assume that there is a pre-existing list of books. You don't need to
support adding or removing books from the library.

* Book Details - As a customer, I'd like the list of all books to include each
books Author and Year Published, so that I can be confident that I have found
the book I am looking for. The book listing should have columns for this information.

* Main Menu - As a customer, instead of automatically seeing the book list, I
would like to see a list of options and be able to choose one. For now, the only
option should be 'List Books'. All future options should be added to this menu also.

* Invalid Menu Option - As a customer, I would like to be notified when I choose
an invalid option with the message “Select a valid option!”, so that I can know
when I need to re-enter my choice.

* Quit - As a customer, I would like to continue choosing options until I choose to 'Quit'.

## Technical Requirements

* All the code must be developed using TDD.
* Biblioteca needs to be a console application. Use your own imagination for any UI elements
