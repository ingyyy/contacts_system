# CLI Contact Book (Python)

A lightweight, interactive Command-Line Interface (CLI) application built in Python that allows users to manage a contact list efficiently. This project demonstrates the practical application of core programming concepts, including functions, loops, conditional statements, and nested data structures (`dictionaries`).

## 🚀 Features

The application supports full **CRUD** (Create, Read, Update, Delete) operations:
*   **Add Contact:** Create a new contact with a unique name, phone number, email, and address. Prevents duplicate entries.
*   **View Contact:** Look up a specific contact by name to display their detailed information.
*   **Edit Contact:** Update existing details (phone, email, or address) dynamically. Leaving a field empty retains its previous value.
*   **Delete Contact:** Safely remove a specific contact from the book without affecting others.
*   **List All Contacts:** Display all saved contacts in a clean, user-friendly, and structured layout.

## 🛠️ Concepts Demonstrated
*   **Nested Dictionaries:** Used for structured and optimized data management (`contact_book[name]['phone']`).
*   **Input Validation:** Handles empty inputs gracefully during updates to prevent data loss.
*   **Control Flow:** Implementation of `while` loops and nested `if-elif-else` structures for an uninterrupted menu-driven experience.

## 💻 How to Run & Sample Output

```text
1. Clone the repository:
   git clone [https://github.com/ingyyy/contacts_system.git](https://github.com/ingyyy/contacts_system.git)

2. Navigate into the folder:
   cd contacts_system

3. Run the script:
   python contact_book.py

--------------------------------------------------
📋 APPLICATION SAMPLE OUTPUT:
--------------------------------------------------
Contact Book Menu:
1. Add Contact
2. View Contact
3. Edit Contact
4. Delete Contact
5. List All Contacts
6. Exit

Name: Alice
Phone: 123-456-7890
Email: alice@example.com
Address: Cairo, Egypt
