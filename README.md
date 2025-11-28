<h1>1. Project Overview</h1>

This project is a menu-driven Book Recommendation System developed in Python.
It allows users to explore books across several genres, view complete genre lists, search for titles, manage a wishlist, and retrieve recently viewed books.
The system is built using core Python programming fundamentals, including dictionaries, lists, sets, loops, user input handling, and functions.
The application runs in a terminal/command-line environment and does not require external libraries.

<h1>2. Features</h1>

<h3>The system includes the following functionalities:</h3>

* Core Functionalities
* Display all available genres.
* Display all books across all genres with author names.
* Recommend books by genre (selected from a menu).
* Search for books by title.
* Add new books to any genre.
* View recently viewed books (maintains a stack of last five entries).
* Add books to a wishlist.
* View wishlist (stored using a Python set to avoid duplicates).

<h3>Program Characteristics</h3>

* Fully menu-driven interface for user-friendly navigation.
* Input validation to avoid program crashes due to invalid entries.
* Modular structure with separate functions for each feature.
* Uses built-in Python data structures: dictionary (for database), list (for stack), set (for wishlist).
* Designed for academic learning, demonstrating multiple Python concepts within one project.

<h1>3. Technologies Used</h1>

* Python 3.x
* Only standard Python libraries (no external dependencies)

<h1>4. Project Structure</h1>
BOOK-RECOMMENDATION-SYSTEM/

│── book_recommendation_system.py         # Main application script
<br>
│── README.md                             # Project documentation

<h1>5. How to Run the Program</h1>
Step 1: Clone or Download the Repository

Clone via Git:

git clone https://github.com/mayanksharma0070/BOOK-RECOMMENDATION-SYSTEM.git


Or download the ZIP file and extract it.

Step 2: Open a Terminal or Command Prompt

Navigate to the project directory:

cd BOOK-RECOMMENDATION-SYSTEM

Step 3: Run the Python Script
python book_recommendation_system.py


or

python3 book_recommendation_system.py

<h1>6. Implementation Approach</h1>

This project is developed using fundamental, non-OOP Python concepts.
The major implementation decisions include:

<h3>Data Representation</h3>

* A dictionary of lists is used as the primary book database, where:

  * Each key represents a genre,
  * Each value is a list of dictionaries, each containing title and author.

 <h3>Functional Design</h3>

  * Every operation (search, display, adding books, genre selection, wishlist management) is implemented as a separate function.
  * The structure promotes readability, maintainability, and logical separation.

<h3> Control Flow</h3>

  * A continuous while loop forms the core of the menu system.
  * User choices are validated to prevent incorrect or unexpected input.
  * Recently viewed books use a stack mechanism, keeping only the last five entries.
  * Wishlist uses a set to avoid duplicate entries.

  <h3>Scalability</h3>

  * New genres or books can be added easily.
  * Additional features can be integrated without restructuring the program.

<h1>7. Key Learnings</h1>

This project demonstrates several core Python programming concepts:

* Use of dictionaries, lists, sets, and nested structures.
* Menu-driven application design.
* Functional decomposition and modular programming.
* Handling user inputs and implementing validation.
* Managing data through stacks and sets.
* Clean terminal output formatting.
* Structuring a Python project for academic presentation.

<h1>8. Future Enhancements</h1>

The system can be extended with more advanced features, such as:

* Graphical User Interface (Tkinter or PyQt)
* Search filter by author
* Sorting books alphabetically or by publication year
* Personalized recommendation algorithm
* Exporting wishlist or history to a file (CSV/JSON)
* Importing book data from external sources

<h1>9. License</h1>

This project is intended for educational and academic use.
You are free to modify, enhance, and integrate it into learning assignments or demonstrations.
