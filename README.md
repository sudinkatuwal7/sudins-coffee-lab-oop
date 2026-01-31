# ☕ Sudin’s Coffee Lab (OOP)

A Python-based **coffee machine simulator** built using **Object-Oriented Programming (OOP)** principles.  
This project was originally implemented using a procedural approach and later **refactored into OOP** to improve modularity, readability, and scalability.

---

## 🚀 Features
- Console-based coffee machine simulation
- Supports multiple drinks (espresso, latte, cappuccino)
- Resource management (water, milk, coffee)
- Coin-based payment system
- Profit tracking and machine reports
- Clean OOP architecture with separated responsibilities

---

## 🧠 OOP Design Overview

The project follows **separation of concerns**, where each class has a single responsibility:

### 📋 `Menu`
- Stores available drinks
- Returns drink options
- Finds drink details based on user input

### ☕ `CoffeeMaker`
- Manages resources (water, milk, coffee)
- Checks if resources are sufficient
- Makes coffee and deducts ingredients

### 💰 `MoneyMachine`
- Handles coin input
- Processes payments
- Tracks and reports total profit

---

## 📂 Project Structure

```bash

sudins-coffee-lab-oop/
│
├── main.py
├── menu.py
├── coffee_maker.py
├── money_machine.py
└── README.md

```


---

##  Run the program

```bash
python main.py
```

## 🔄 Procedural vs OOP Refactor
- Before

   - Global variables for resources and profit

   - Standalone functions

   - Harder to maintain and scale

- After

   - Encapsulated data inside classes

   - Cleaner and more readable code

   - Easier to extend and debug

   - This refactor demonstrates why and when OOP is useful in real-world Python projects.

## 🛠️ Technologies Used

- Python 3

- Object-Oriented Programming (OOP)

## 🎯 Learning Goals

- Understand OOP concepts in Python

- Practice class-based design

- Learn clean project structuring

- Refactor procedural code into OOP

## 📌 Future Improvements

- Add more drink options

- Persist resources using files

- Add unit tests

- Implement a GUI version

## 👤 Author

### Sudin Katuwal

