# 🚆 E-Ticketing Application

An **E-Ticketing Train Reservation System** built in **Java** using **Object-Oriented Programming (OOP) principles**, **Design Patterns**, and an **MVC architecture**. The application allows users to book, cancel, and manage train tickets with a user-friendly **Java Swing (JFrame)** interface, while maintaining structured code design and scalability.

---

## ✨ Features
- 🎟 **Book and Cancel Train Tickets**
- 👤 **User Registration & Login**
- 📅 **View Train Schedules & Availability**
- 🗄 **Database Integration (JDBC)** for storing user and ticket data
- 🖥 **Java Swing (JFrame) GUI** for interactive desktop usage
- 📐 **MVC Architecture** for clean separation of concerns

---

## 🏗 Design Patterns Used
This project demonstrates the use of multiple **GoF design patterns**:

1. **Singleton** – Ensures a single database connection instance throughout the application.  
2. **Factory** – Creates different types of tickets or users dynamically without exposing instantiation logic.  
3. **Builder** – Helps construct complex ticket objects step by step.  
4. **Command** – Encapsulates booking and cancellation operations, allowing easy undo/redo or action logging.  
5. **Strategy** – Provides flexible payment methods (e.g., card, wallet, net banking) that can be swapped at runtime.  

---

## 🏛 Architecture
The project follows the **Model-View-Controller (MVC)** pattern:
- **Model** – Business logic, ticket management, user data, and database interaction.  
- **View** – GUI built using **Java Swing (JFrame)**.  
- **Controller** – Handles user actions, updates model and view accordingly.  

---

## ⚙️ Tech Stack
- **Language:** Java (OOP)  
- **GUI:** Java Swing (JFrame)  
- **Database:** JDBC (MySQL/Oracle/any relational DB)  
- **Architecture:** MVC + Design Patterns  

---

## 🚀 How to Run
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/e-ticketing-system.git
