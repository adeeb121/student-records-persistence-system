# 📚 Student Records Persistence & Export System

A Python-based command-line student management system that stores student records permanently using JSON, exports data to CSV, and maintains an activity log using text files.

## 📌 Project Overview

This project allows users to add, search, display, and manage student records. Student information is stored in a JSON file so that records can be loaded again when the program runs next time.

The system also provides CSV export functionality and maintains a timestamped activity log to track important operations such as adding, updating, and exporting records.

## ✨ Features

- Add new student records.
- Store student ID, name, department, and subject marks.
- Validate marks between 0 and 100.
- Prevent duplicate student IDs.
- Save records permanently in a JSON file.
- Load existing records when the program starts.
- Search students using their ID.
- Display all saved student records.
- Export student data to CSV format.
- Maintain a timestamped activity log.
- Demonstrate different text file reading and writing methods.
- Perform JSON string serialization and deserialization.
- Handle missing files and malformed JSON safely.

## 📂 Project Structure

```text
student_records_system/
│
├── main.py
├── students.json
├── students.csv
├── activity_log.txt
└── README.md
```

## 🛠️ Technologies Used

- Python 3
- JSON
- CSV
- Text File Handling
- Command Line Interface (CLI)

## 📖 Python Concepts Used

### File Handling
- `open()`
- `with` statement
- File modes: `r`, `w`, `a`
- `read()`, `readline()`, `readlines()`
- `write()`, `writelines()`

### JSON
- `json.load()`
- `json.dump()`
- `json.loads()`
- `json.dumps()`
- Serialization and Deserialization

### CSV
- CSV module
- `csv.writer()` / `csv.DictWriter()`
- Writing header rows
- CSV export

### Other Concepts
- Lists and Dictionaries
- Functions
- Input Validation
- Exception Handling
- `os` module
- `datetime` module

## 🧾 Example JSON Data

```json
{
    "S101": {
        "name": "Aman",
        "department": "CSE",
        "marks": {
            "Python": 78,
            "Maths": 65,
            "DS": 88
        }
    }
}
```

## ▶️ How to Run

**1. Clone the repository**

```bash
git clone YOUR_REPOSITORY_URL
```

**2. Open the project folder**

```bash
cd student_records_system
```

**3. Run the Python program**

```bash
python main.py
```

## 📦 Requirements

- Python 3 installed.
- No external packages required.
- Uses Python's built-in `json`, `csv`, `os`, and `datetime` modules.

## 🎯 Learning Objective

The main objective of this project is to understand how Python handles permanent data storage using files. It provides practical experience with JSON serialization, CSV export, text file operations, and safe data management.

## 👨‍💻 Author

**Adeeb Hami**

B.Tech CSE (AI/ML) Student

