<!-- HEADER SECTION -->
<div align="center">

# Student Grade Management System

**A modern desktop application for student academic records, GPA calculation, and grade analytics.**

<!-- BADGES -->
[![Platform](https://img.shields.io/badge/Platform-Desktop%20%7C%20Windows%20%26%20Linux-0A66C2?style=flat-square)](#)
[![Author](https://img.shields.io/badge/Author-Shawkat%20Hossain%20Maruf-black?style=flat-square)](https://shawkath646.dev)
[![Ecosystem](https://img.shields.io/badge/Ecosystem-clouburstlab-2563EB?style=flat-square)](https://clouburstlab.com)
[![Course](https://img.shields.io/badge/Course-Application%20of%20Programming%20Language-orange?style=flat-square)](#)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](#-license)
[![Python](https://img.shields.io/badge/Python-3.13-blue?style=flat-square&logo=python&logoColor=white)](#)

</div>

---

### 📋 Project Overview

| Property | Details |
| :--- | :--- |
| **Author** | [Shawkat Hossain Maruf](https://shawkath646.dev) |
| **Course** | Application of Programming Language |
| **Platform** | Desktop Application (Tkinter GUI) |
| **Period / Timeline** | Fall 2025 (Nov 2025) |
| **Status** | Completed / Academic Project |
| **Primary Stack** | Python 3.13, Tkinter / CustomTkinter, SQLite3, ReportLab |

---

> [!IMPORTANT]
> **Academic Coursework Notice**  
> This project was developed as a term project for the **Application of Programming Language** course. It demonstrates graphical user interface (GUI) engineering, persistent relational data modeling, defensive input validation, and modular application architecture in Python.

---

## 🎯 Purpose & Problem Statement

### Why It Exists
Manual tracking of student academic performance across semesters is prone to human error, disorganized records, and inefficient calculation of weighted GPAs. This application provides academic administrators and instructors with an intuitive desktop environment to record, analyze, and manage student performance.

### What It Solves
- **Automated GPA & Grade Calculations:** Converts percentage scores into 4.0-scale GPA points and letter grades (A+, A, B+, etc.) based on standard university grading rubrics.
- **Persistent Relational Storage:** Implements an embedded SQLite database ensuring seamless offline storage, transactional integrity, and quick record retrieval.
- **Academic Analytics & Reporting:** Provides summary statistics (class averages, highest/lowest scores, pass rates) and printable reports.

---

## 💡 Key Features & Architecture

- **Student Profile Management:** Add, update, delete, and view comprehensive student details (ID, Name, Department, Enrollment Status).
- **Course & Marks Registration:** Register course codes, credit hours, and numerical marks with automated validation safeguards.
- **Statistical Dashboard:** Computes cumulative GPA (CGPA), grade distributions, and performance summaries in real-time.
- **Relational Data Layer (`app/db.py`):** Clean separation between business logic, database queries, and the GUI interface using the Model-View architecture.
- **Input Sanitization:** Robust error handling preventing SQL injection, duplicate key entries, and out-of-range mark inputs.

---

## 🛠️ Tech Stack & Dependencies

- **Language:** Python 3.13
- **GUI Framework:** Tkinter / Modern Tk widgets
- **Database:** SQLite3 (Native relational storage)
- **Reporting & Exports:** CSV export, ReportLab (PDF generation)
- **Code Quality:** Flake8, Black, modular packaging (`app/`)

---

## 🚀 Getting Started

### Prerequisites
- Python 3.10 or higher installed.

### Installation & Setup

```bash
# 1. Clone the repository
git clone https://github.com/shawkath646/academic-python-student-grade-manager.git
cd academic-python-student-grade-manager

# 2. Create and activate a virtual environment
python -m venv venv
# On Windows:
venv\Scriptsctivate
# On macOS/Linux:
source venv/bin/activate

# 3. Install dependencies (if any external packages required)
pip install -r requirements.txt # (or run directly with built-in modules)

# 4. Launch the application
python -m app.main
```

---

## 🗂️ Project Structure

```
academic-python-student-grade-manager/
├── app/
│   ├── __init__.py
│   ├── config.py             # Application settings & color themes
│   ├── db.py                 # SQLite database schema & queries
│   ├── grading.py            # GPA and letter-grade calculation algorithms
│   ├── gui.py                # Tkinter main interface & dialogs
│   └── main.py               # Application entry point
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── PROJECT_ORGANIZATION.md
├── QUICKSTART.md
├── README.md
└── requirements.txt
```

---

## 🤝 Contributing & Support

Because this repository houses personal academic coursework, pull requests modifying project scope are not accepted. Feedback or bug reports are welcome via the [Issue Tracker](https://github.com/shawkath646/academic-python-student-grade-manager/issues).

---

## 📄 License

Distributed under the [MIT License](LICENSE). See `LICENSE` for more information.

---

<!-- BRANDING FOOTER -->
<div align="center">
  <sub>Engineered by</sub><br/>
  <strong><a href="https://shawkath646.dev">Shawkat Hossain Maruf</a></strong>
  <br/><br/>
  <sub>A product of</sub><br/>
  <a href="https://clouburstlab.com" target="_blank" rel="noopener noreferrer">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://assets.clouburstlab.com/branding/icon_dark.png">
      <source media="(prefers-color-scheme: light)" srcset="https://assets.clouburstlab.com/branding/icon_light.png">
      <img alt="clouburstlab" src="https://assets.clouburstlab.com/branding/icon_light.png" width="230">
    </picture>
  </a>
</div>
