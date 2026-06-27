# 👨‍💼 Employee Management System

A simple **command-line based Employee Management System** built using Python. This project allows users to add, view, update, delete, and persist employee records — all through an interactive menu, without using any external libraries or JSON.

---

## 📌 Features

- ➕ **Add Employee** — Store employee ID, name, age, salary, and department  
- 📋 **View Employees** — Display all employee records in a readable format  
- ✏️ **Update Employee** — Modify existing employee details (leave fields blank to skip)  
- ❌ **Delete Employee** — Remove an employee record by ID  
- 💾 **Save to File** — Persist employee data to a `.txt` file (custom format, no JSON)  
- 📂 **Load from File** — Reload saved employee data back into the program  
- 🔁 **Interactive Menu** — Loop-based CLI menu until the user chooses to exit  

---

## 🗂️ File Structure

```
├── employ.py        # Main Python script containing all functionality
└── README.md        # Project documentation
```

---

## ⚙️ Requirements

- Python 3.x

No external/third-party libraries are required — built entirely using Python's standard features.

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/rejitha2503/<your-repo-name>.git
   ```
2. Navigate to the project folder:
   ```bash
   cd <your-repo-name>
   ```
3. Run the script:
   ```bash
   python employ.py
   ```

---

## 🖥️ Menu Options

```
1. Add Employee
2. View Employee
3. Update Employee
4. Delete Employee
5. Save to file
6. Load From file
7. Exit
```

| Option | Description |
|--------|-------------|
| 1 | Add a new employee record (ID, Name, Age, Salary, Department) |
| 2 | View all currently stored employee records |
| 3 | Update one or more fields of an existing employee |
| 4 | Delete an employee record using their ID |
| 5 | Save all employee data to a text file |
| 6 | Load employee data from a previously saved text file |
| 7 | Exit the program |

---

## 💾 Data Storage Format

Employee data is saved in a plain text file using the format:

```
emp_id:-> Name,Age,Salary,Department
```

Example:
```
101:-> Rejitha,22,45000,IT
102:-> Kumar,25,38000,HR
```

> ⚠️ Note: Since data is stored as comma-separated text (not JSON), make sure employee names/departments don't contain commas.

---

## 🧠 Concepts Used

- Python Dictionaries for in-memory data storage
- Functions and modular code design
- File handling (read/write) without JSON
- Exception handling (`try-except`)
- Loop-based CLI menu system

---

## 🔮 Future Improvements

- [ ] Add JSON/CSV-based storage for more reliable data persistence
- [ ] Add input validation (e.g., age/salary should be numeric)
- [ ] Add search functionality (search by name/department)
- [ ] Add sorting (by salary, age, etc.)
- [ ] Convert to a GUI app using Tkinter
- [ ] Add unit tests

---

## 👩‍💻 Author

**Rejitha**  
Final Year B.E. CSE Student | Aspiring Data Analyst  
[LinkedIn](https://linkedin.com/in/rejitha2503) | [GitHub](https://github.com/rejitha2503)
