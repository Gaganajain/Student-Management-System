<div align="center">

# 🏫 Student Management System

**A desktop app to record student marks, auto-calculate results and keep everything in Excel**

![Python](https://img.shields.io/badge/Python-3.9+-3776AB?logo=python&logoColor=white)
![Tkinter](https://img.shields.io/badge/GUI-Tkinter-blue)
![Excel](https://img.shields.io/badge/Storage-Excel%20(.xlsx)-217346?logo=microsoftexcel&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green)

</div>

---

## 📌 Overview

Teachers often track marks in scattered spreadsheets and calculate totals by hand. This app gives them a simple form: enter a student's roll number, name and marks in three subjects, and it **calculates the total, average and grade**, then **saves the record to `students.xlsx`** so it can be opened in Excel at any time.

## ✨ Features

- 📝 Add students with roll number, name and three subject marks
- 🧮 Automatic **total**, **average** and **grade** (A+ to F)
- 💾 Records saved to an Excel file (`students.xlsx`); existing records are kept
- 🔁 Saving an existing roll number **updates** that student instead of duplicating
- 📋 Table of all students; click a row to load it into the form
- 🗑️ Delete a selected student
- ✅ Input validation (required fields, marks between 0 and 100)

## 🧮 Grading Scale

| Average | Grade |
|---|---|
| 90 and above | A+ |
| 75 – 89 | A |
| 60 – 74 | B |
| 50 – 59 | C |
| 35 – 49 | D |
| Below 35 | F |

## 🖥️ App Layout

```
┌──────────────── STUDENT MARKS DETAILS ────────────────┐
│ Roll No    [        ]    Student Name [            ]  │
│ Subject 1  [        ]    Subject 2    [            ]  │
│ Subject 3  [        ]    Total        [ auto       ]  │
│ Average    [ auto   ]    Grade        [ auto       ]  │
│                                                       │
│  [CALCULATE & SAVE]   [CLEAR]   [DELETE SELECTED]     │
│ ┌───────────────────────────────────────────────────┐ │
│ │ Roll │ Name │ Sub1 │ Sub2 │ Sub3 │ Total │ Avg │ G │ │
│ │ 101  │ Asha │  88  │  92  │  79  │  259  │86.33│ A │ │
│ └───────────────────────────────────────────────────┘ │
└───────────────────────────────────────────────────────┘
```

## 🚀 Getting Started

```bash
git clone https://github.com/Gaganajain/Student-Management-System.git
cd Student-Management-System
pip install -r requirements.txt
python main.py
```

`students.xlsx` is created in the same folder the first time you save a student.

## 🛠️ Tech Stack

| Area | Tools |
|---|---|
| Language | Python |
| GUI | Tkinter + ttk Treeview |
| Storage | openpyxl (Excel `.xlsx`) |

## 🔮 Future Improvements

- Search and filter students
- Charts of class performance
- Export a report card as PDF
- SQLite database option

## 👩‍💻 Author

**Gagana Jain A** · [GitHub](https://github.com/Gaganajain)

## 📄 License

This project is licensed under the [MIT License](LICENSE).
