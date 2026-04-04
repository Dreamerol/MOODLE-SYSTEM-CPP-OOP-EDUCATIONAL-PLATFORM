This is my OOP Homework project for Student System :)

# 🎓 Moodle System (C++ Project)

This project is a simplified implementation of a **Moodle-like educational system**, designed to manage **users, students, and academic operations** using Object-Oriented Programming principles in C++.

---

## 📖 Overview

The system simulates a learning management environment where different types of users interact through structured operations such as **task management, grading, and notifications**.  

It focuses on building a **modular and extensible architecture**, allowing different functionalities to be executed through well-defined commands and class interactions.

---

## 👥 System Entities

The project is built around key entities:

- **Users** – Base abstraction representing all participants in the system  
- **Students** – Specialized users with extended capabilities such as submitting tasks and receiving grades  

The design allows easy extension for additional roles while maintaining clean separation of responsibilities.

---

## 🧠 OOP Concepts Applied

This project demonstrates core **Object-Oriented Programming principles**:

- **Encapsulation** – Data and behavior are contained within classes  
- **Inheritance** – Students extend the base User class  
- **Polymorphism** – Unified handling of different operations and entities  
- **Abstraction** – Simplified interfaces for complex system behavior  

---

## ⚙️ Design Pattern: Command Pattern

A key part of the system architecture is the use of the **Command Pattern**.

Instead of directly executing actions, operations are encapsulated into **command objects**, which allows:

- Decoupling of **request invocation** from **execution logic**  
- Flexible addition of new commands without modifying existing code  
- Clear separation of system operations  

Each action (e.g., uploading a task, sending a notification, assigning a grade) is represented as a **command**, making the system more modular and maintainable.

---

## 🔄 Core Functionalities

### 📩 Email Notifications
- Simulates sending notifications to users  
- Triggered by system events such as task submissions or grading  
- Encapsulated as commands for consistent handling  

---

### 📤 Task Uploading
- Students can upload tasks/assignments  
- The system processes submissions through command execution  
- Ensures structured handling of input and validation  

---

### 📊 Grading System
- Tasks can be evaluated and assigned grades  
- Grades are associated with specific students and submissions  
- Supports clear tracking of academic performance  

---

### 🔁 Command-Based Operations
All major actions in the system are handled through commands, including:

- Creating users  
- Uploading assignments  
- Sending notifications  
- Assigning grades  

This approach ensures that operations are:

- Reusable  
- Easy to extend  
- Clearly organized  

---

## 🛠️ Technical Features

- Class-based architecture with clear responsibilities  
- Use of **design patterns (Command Pattern)**  
- Modular and scalable system design  
- Clean separation between logic and execution  
- Structured handling of user actions and system events  

---

## 💡 Learning Outcomes

By working on this project, you will:

- Understand how to design a **real-world system using OOP**  
- Learn how to apply **design patterns in practice**  
- Gain experience with **command-based architectures**  
- Improve skills in **system design and modular programming**  
- Understand how backend systems manage **operations like tasks, notifications, and grading**  

---

## 📌 Conclusion

This project demonstrates how a real-world learning platform can be modeled using **C++**, combining **Object-Oriented Programming and design patterns** to create a structured, extensible, and maintainable system.
