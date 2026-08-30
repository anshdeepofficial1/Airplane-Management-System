# ✈️ Airplane Management System (C++)`n`n<p align="center">`n  <a href="https://github.com/sponsors/anshdeepofficial"><img src="https://img.shields.io/badge/Sponsor-%E2%9D%A4-EA4AAA?style=for-the-badge&logo=githubsponsors&logoColor=white" alt="Sponsor on GitHub" height="40" /></a>`n  <a href="https://buymeacoffee.com/anshdeepofficial"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me a Coffee" height="40" /></a>`n</p>

## 📝 Project Overview

The **Airplane Management System** is a C++ console-based project designed to simulate airport flight management operations. It allows administrators to **add, view, update, and manage flights, assign runways, display weather conditions, and save flight data** to a file for record-keeping.

This project demonstrates the practical application of **Object-Oriented Programming (OOP)** concepts such as classes, inheritance, encapsulation, and abstraction. It also showcases the use of **file handling**, **randomization**, and **data structures** (like vectors) to manage dynamic lists of flights efficiently.

---

## 🚀 Features

* **Add New Flight:** Enter flight details such as number, airline, origin, destination, and arrival time.
* **View All Flights:** Display all recorded flights with their status and assigned runway.
* **Update Flight Status:** Change flight status to *Arriving*, *Delayed*, or *Landed*.
* **Assign Runway:** Assign a runway number to a specific flight.
* **Weather Simulation:** Randomly generate weather conditions (Clear, Rainy, Foggy, Stormy) that affect flight operations.
* **Save Flight Data:** Save flight information to a text file (`flights.txt`) for record storage.

---

## ⚙️ Concepts Used

* **Classes and Objects** – to structure data and functionality.
* **Encapsulation** – to protect flight data through controlled access.
* **Abstraction** – to simplify operations for the end-user.
* **Polymorphism** – for potential future extensions using virtual functions.
* **File Handling** – for saving and retrieving flight information.
* **Randomization** – for generating weather conditions.
* **Vectors (STL)** – to dynamically store and manage flight objects.

---

## 💡 How It Works

1. The program displays a **menu** with options to manage flights.
2. Users can add new flights, update their status, assign runways, or check current weather.
3. Weather is generated randomly, affecting flight messages.
4. Data can be saved to `flights.txt` for future use.

Example file content:

```
AI202,Arriving
BA304,Delayed
QR401,Landed
```

---

## 🧩 Class Structure

### `Flight`

Handles flight details and displays flight information.

### `Weather`

Generates and displays random weather conditions.

### `Airport`

Manages all operations such as adding, updating, displaying, and saving flights.

---

## 🧠 Learning Outcomes

* Understand and apply **Object-Oriented Programming** in C++.
* Learn how to handle **files** and **data persistence**.
* Implement **menu-driven** programs using loops and conditionals.
* Work with **vectors** for dynamic data management.
* Combine multiple programming concepts into a single integrated project.

---

## 🛠️ Technologies Used

* **Language:** C++
* **Compiler:** GCC / MinGW
* **IDE:** Code::Blocks / Dev-C++ / Visual Studio Code
* **Libraries:**

  * `<iostream>` – Input/Output operations
  * `<fstream>` – File handling
  * `<vector>` – Dynamic data storage
  * `<cstdlib>` and `<ctime>` – Randomization utilities

---

## 📚 Future Enhancements

* Load previously saved flight data on program start.
* Add **passenger** and **crew management** modules.
* Include **real-time weather data** using APIs.
* Develop a **graphical user interface (GUI)**.
* Integrate a **database system (MySQL)** for scalable storage.

---

## 🏁 Conclusion

The **Airplane Management System** is a beginner-friendly yet feature-rich C++ project that provides hands-on experience with OOP concepts, file handling, and structured programming. It serves as a strong foundation for students and developers who wish to explore real-world system design and C++ application development.
