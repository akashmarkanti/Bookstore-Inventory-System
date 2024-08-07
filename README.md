# Bookstore Inventory System

This project is a simple bookstore inventory system built with Flask. It allows you to add, edit, and delete books from an inventory. The project includes a web interface with basic styling using CSS.

## Features

- Add new books to the inventory
- Edit details of existing books
- Delete books from the inventory
- View a list of all books in the inventory

## Technologies Used

- Python
- Flask
- Flask-SQLAlchemy
- Flask-WTF
- HTML/CSS

## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.x
- pip (Python package installer)

## Project Setup

Follow these steps to set up and run the project:

### Create a virtual environment:
- python -m venv bookstore_env

### Activate the virtual environment:
- bookstore_env\Scripts\activate

### Install the required dependencies:
- pip install -r requirements.txt

## Project Structure:

bookstore-inventory-system/
│
├── app.py
├── config.py
├── models.py
├── forms.py
├── static/
│   └── style.css
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── add_book.html
│   └── edit_book.html
└── requirements.txt

## Running the Application:
- python app.py

### Open your web browser and navigate to:
- http://127.0.0.1:5000/
