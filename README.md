# Library Automation System (February 2023)

## 📖 Overview
This is a **library automation system** developed in **February 2023** to help manage books, track borrowing records, and analyze book-related data efficiently. The project was created as a Python-based solution to automate various tasks within a library environment.

⚠ **Note:** This is an **archived project** and is no longer actively maintained.

## 📌 Features
The system consists of four main components:

1. **📚 New Book Entry**  
   - Allows to add new books to the system.
   - Stores book details such as title, author, publisher, genre, ISBN, and location of the book (floor, Bookshelf).
   - After entering the necessary information, the system provides details such as the floor and shelf location of the desired book, making it easier and more efficient for library members to find what they need. This information is then stored in a CSV file, serving as a simple database system.
   
2. **🔍 Monitoring Books**  
   - The system allows users to view all books and search for a specific title using various book attributes. Additionally, users can filter the library’s collection by author, making it easy to find all books by a particular author simply by entering their name. If a book has been previously borrowed, the system will notify the user with an error message.
     - Observe every book with filtering.
     - Status of the book (Borrowed or not)
   
3. **🔄 Borrow System**  
   - By entering the book's barcode number, the system records the requested book's information along with the borrowing date, and provides the member with the book for checkout. Upon return, the book's barcode is entered again, updating the system and changing the book’s status to returned.
   - Borrowing
     - Barcode of the book
     - Date of the borrowing
   - Returning
     - Barcode of the book

   
4. **📊 Analysis System**  
   - The system can display the book type ratios and also provides information on which books have been borrowed this month, as well as the new additions to the collection.
     - Display the book type ratios
     - Which new books are entered
     - Borrowed books


## 🚀 Installation & Usage
Clone the repository:
   ```sh
   git clone https://github.com/mraknar/library-automation-2023.git
   cd library-automation-2023
   ```

## 🏛️ Project Status
As this project was developed in **February 2023**, it is no longer actively maintained. However, feel free to fork and modify it for your own use!

---

💡 *For any questions, feel free to open an issue or reach out!*

