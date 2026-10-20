# Student Management Python Basic

[![Status](https://img.shields.io/badge/status-active-brightgreen)](https://github.com/DaniDevGS/student-management_python-basic)
[![License](https://img.shields.io/badge/license-CC_BY--ND_4.0-lightgrey)](https://creativecommons.org/licenses/by-nd/4.0/)
[![Python](https://img.shields.io/badge/Python-3.6%2B-blue?logo=python)](https://python.org)
[![Technology](https://img.shields.io/badge/Technology-CLI%20%26%20JSON-yellow)](https://github.com/DaniDevGS/student-management_python-basic)
[![Code Style](https://img.shields.io/badge/code%20style-PEP8-brightgreen)](https://pep8.org)

![Screenshot of the StudentFlow system in the terminal](https://images.unsplash.com/photo-1624953587687-daf255b6b80a?fm=jpg&q=60&w=800&h=400&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8M3x8cHl0aG9uJTIwcHJvZ3JhbW1pbmd8ZW58MHx8MHx8fDA%3D)

<br>

A basic academic management system: a **simple and lightweight** application developed entirely in **Python**. Designed to run in the command-line interface (CLI), it allows **students** to register their information easily, while providing **administrators** with a comprehensive view and tools to manage the data.

## ✨ Key Features

- Colorful command-line interface (using Colorama)
- Built-in data validation
- Data persistence using JSON files
- Colorful, user-friendly terminal interface
- Student and administrator management

## 🛠️ Technologies Used

<!-- [![My Skills](https://skillicons.dev/icons?i=python)](https://github.com/DaniDevGS/computer-academy_frontend-project) -->

- **Python:** Version 3.6+
- **Colorama:** Used to add colors and styles to the terminal interface.
- **JSON:** Used as a data storage system for persistence.

## ⚙️ Prerequisites

- Python 3.6 or later
- pip (Python package manager)

## 🚀 Installation

1. Clone the repository:

```bash
git clone https://github.com/DaniDevGS/student-management_python-basic
cd student-management_python-basic
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

## 🚀 Running the Application

1. Open a terminal and run:

```bash
python main.py
```

### 🔑 Test Credentials (Administrator Mode)

To access the advanced features in the administrator menu, the system requires a password.

```text
Administrator: admin123
```

⚠️ **Note:** This is a test credential intended for development.

## 📁 Project Structure

```text
student-management_python-basic/
├── utils/
│   ├── components/
│   │   ├── statistics/ # Statistics and reporting logic
│   │   │   └── stats.py
│   │   └── universitys.py # University-specific data or logic
│   ├── database/
│   │   └── json.py # Module for handling JSON files
│   └── menu.py # CLI menu management module
├── estudiantes.json # Data storage
├── main.py # Main application entry point
└── requirements.txt
```
