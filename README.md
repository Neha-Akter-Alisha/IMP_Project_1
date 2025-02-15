# Inventory Management System

## Introduction
This is a simple **Inventory Management System** built using **Python (Flask) and Flask-SQLAlchemy**. It allows users to **add, update, delete, and view** inventory items efficiently. The project is designed to help small businesses manage their stock in a structured manner.

## Features
- Add new inventory items with details.
- Update existing inventory records.
- Delete unwanted inventory items.
- View all available inventory items.

## Installation
Follow these steps to set up and run the project on your local machine.

### Prerequisites
- Install **Python 3** (Ensure it is added to the system path)
- Install **Flask** and required dependencies

### Setup Instructions
1. **Clone the Repository**
   ```bash
   git clone https://github.com/Neha-Akter-Alisha/IMP_Project_1.git
   cd IMP_Project_1
   ```
2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```
3. **Set Up the Database**
   ```bash
   python
   >>> from app import db
   >>> db.create_all()
   >>> exit()
   ```
4. **Run the Flask Application**
   ```bash
   python app.py
   ```
5. Open a web browser and navigate to `http://127.0.0.1:5000/` to access the Inventory Management System.

## Working of the Project
- The system maintains an **inventory database** using Flask-SQLAlchemy.
- Users can **add new items** with details like name, quantity, and price.
- Items can be **edited or deleted** if required.
- A structured **frontend interface** helps users interact with the system easily.

## DSA Concepts Used
This project incorporates fundamental **Data Structures and Algorithms (DSA)** concepts, including:
- **Binary Search**: Used to quickly search for inventory items.
- **Hashing**: Used in Flask-SQLAlchemy for efficient database lookups.
- **CRUD Operations**: Implemented using Flask models and views.

## Contributions
Feel free to fork this repository, enhance the system, and submit pull requests.

## License
This project is open-source and available under the **MIT License**.

## Contact
For any issues or improvements, feel free to reach out or open an issue on GitHub.

