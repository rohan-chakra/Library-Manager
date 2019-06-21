# Library-Manager
## What it is:
A GUI Based Java Program that asks the user for the Book Name, the Author's Name, the Genre of the book and finally the cost.
Using all these details it generates a unique ID. Every book is assigned its own unique ID and finally the books are sorted according to their ID's.
Java-Swing was used to make the GUI.

## Why is it useful:
A library based program where the Unique ID is based on the particular combination of that book entered by the user sets apart every book and help maintain a sorted record of the books.

## Hash used to determine the unique ID:
The ASCII equivalent of the letters in the book details entered by the user are added and subtracted from a specific number after moded by the number of books currently in the library.
Basically: Unique ID = Specific NUM-(Sum of ASCII values)%n
Where n = number of books currently in library.
This hash sets every book with a different ID.


