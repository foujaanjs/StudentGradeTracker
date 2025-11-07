# 🎓 Student Grade Tracker (Java)

A simple console-based **Java** application to manage student names and grades.  
This project demonstrates **OOP concepts**, **file handling**, and **collections** — perfect for beginners learning core Java development.

---

## 📑 Table of Contents
- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [How to Run](#how-to-run)
- [Sample Output](#sample-output)
- [Screenshots](#screenshots)
- [Future Enhancements](#future-enhancements)
- [Author](#author)
- [License](#license)

---

## 🧩 About the Project

The **Student Grade Tracker** allows users to:
- Add students and their marks
- Calculate each student’s average
- Identify the class topper
- Save results to a file (`students.txt`)

This is a great project for students who want to **practice object-oriented programming (OOP)** and build a small but real-world Java application.

---

## ✨ Features

| Feature | Description |
|----------|--------------|
| ➕ Add Student | Input student name and marks |
| 📋 Display All | View all students and their average |
| 🏆 Show Topper | Identify student with highest average |
| 💾 Save Data | Save all records to `students.txt` in the root folder |
| 🚪 Exit | Quit the program gracefully |

---

## ⚙️ Tech Stack
- **Language:** Java (JDK 8+)
- **Concepts:** OOP, File I/O, Arrays, Loops
- **Tools:** VS Code / IntelliJ / Eclipse
- **Version Control:** Git + GitHub

---

## 📁 Project Structure

StudentGradeTracker/
├── .vscode/
│ └── launch.json
├── src/
│ ├── Student.java
│ ├── GradeManager.java
│ └── Main.java
├── screenshots/
│ ├── menu.png
│ ├── add_student.png
│ ├── display.png
│ └── topper.png
├── students.txt
├── README.md
└── .gitignore


---

## 🚀 How to Run

### 🧩 Option 1: Using VS Code
1. Open the project folder in VS Code.  
2. Make sure the **Extension Pack for Java** is installed.  
3. Right-click on `Main.java` → click **Run Java**.

### 🧩 Option 2: Using Command Line
```bash
cd StudentGradeTracker
javac src/*.java
java -cp src Main


The output file students.txt will appear in your project root folder.

🖥️ Sample Output
1. Add Student
2. Display All
3. Show Topper
4. Save
5. Exit
Choose: 1
Enter student name: Alice
Enter marks (comma-separated): 90,85,95
Student added successfully!

Choose: 3
Topper: Alice - Marks: [90, 85, 95] - Average: 90.0

Choose: 4
Saved successfully at: C:\Users\Foujaan\StudentGradeTracker\students.txt

📸 Screenshots
Action	Screenshot
Main Menu	

Add Student	

Display Students	

Topper Output	

📝 Save screenshots inside a /screenshots folder.

🧠 Future Enhancements

✅ Add grade letters (A, B, C, etc.)

✅ Import/Export data using CSV

✅ Build GUI using JavaFX

✅ Connect to MySQL database

👨‍💻 Author

Foujaan Javith
💻 GitHub: https://github.com/foujaanjs

🌐 LinkedIn: https://www.linkedin.com/in/foujaan-javith-45b243258/

 

📜 License

This project is licensed under the MIT License — you’re free to use and modify it for learning and portfolio purposes.

⭐ If you found this project helpful, please give it a star on GitHub!