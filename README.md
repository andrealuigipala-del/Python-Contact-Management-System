# Python Contact Management System

A **command-line contact management application** developed in **Python** using **Object-Oriented Programming (OOP)**.

The application separates contact representation from contact book management and provides an interactive terminal interface for creating, viewing, searching, modifying, and deleting contacts.

Contact data is persisted in a **JSON file**, with automatic loading at application startup and automatic saving after operations that modify the contact book.

## Features

- **Add contacts** with name, surname, phone number, and email
- **Display** all saved contacts
- **Search** contacts by name or surname
- **Modify** existing contact information
- **Delete** contacts with confirmation
- **Input validation** for names, phone numbers, and email addresses
- **JSON persistence** for storing contact data
- **Automatic data loading** when the application starts
- **Automatic data saving** after contact modifications
- Handling of **multiple search results** when modifying or deleting contacts
- Interactive **Command-Line Interface (CLI)**

## Technologies

- **Python**
- **Object-Oriented Programming (OOP)**
- **JSON**
- **Command-Line Interface (CLI)**

## Project Structure

The application is structured around two main classes:

- `Contatto` — represents an individual contact and manages its data.
- `Rubrica` — manages the collection of contacts and provides methods for adding, searching, deleting, saving, and loading contacts.

Additional functions handle the user interface, input validation, and interaction with the contact book.

## Data Persistence

Contacts are stored in a JSON file named `contatti.json`.

The application automatically attempts to load existing contacts when it starts. Changes to the contact book are saved to the JSON file during the relevant operations.

## How to Run

Clone the repository:

```bash
git clone <repository-url>
cd <repository-name>
