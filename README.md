# Form_Validation_Project
# 🧾 Python Form Validation using Regular Expressions

This project is a command-line form validator built using Python. It uses the `re` module to validate inputs such as name, date of birth, email, mobile number, and gender. Once validated, the information is saved to a text file (`details.txt`).

## 📌 Features

- Interactive user input via the command line
- Input validation using `re.compile()` and `pattern.fullmatch()`
- Supports validation for:
  - Name
  - Date of Birth (DD-MM-YYYY)
  - Email (only Gmail addresses)
  - Mobile Number (starting with 7, 8, or 9)
  - Gender (Male or Female)
- Saves validated data to a file

## 🧪 Validated Fields and Regex Patterns

| Field           | Pattern                        | Description                                |
|----------------|--------------------------------|--------------------------------------------|
| Name           | `^[A-Za-z ]+$`                 | Alphabets and spaces only                  |
| Date of Birth  | `\d{2}-\d{2}-\d{4}`            | Format: DD-MM-YYYY                         |
| Email ID       | `^[a-z0-9]+@gmail.com$`        | Gmail addresses in lowercase only          |
| Mobile Number  | `^[789]\d{9}$`                 | Starts with 7/8/9 and 10 digits total      |
| Gender         | `^Male|Female$`                | Case-sensitive match for Male or Female    |

## 📂 Files

- `252e3e5f-22b7-4d5e-b729-73bd2a487d3b.py`: Main validation script
- `details.txt`: Output file storing user details

## ▶️ How to Run

1. Make sure you have Python 3 installed.
2. Run the script:
   ```bash
   python 252e3e5f-22b7-4d5e-b729-73bd2a487d3b.py
