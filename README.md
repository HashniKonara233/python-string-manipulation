# 📧 Email Username Extractor

A beginner-friendly Python project that extracts the username from an email address using string methods and slicing.

## 📌 Project Overview

This project demonstrates how to work with strings in Python by finding the position of the `@` symbol and extracting everything before it.

For example, given the email address `alice.johnson@company.com`, the program extracts `alice.johnson` as the username.

## ⚙️ How It Works

1. Store an email address in a variable named `email`.
2. Use the `.find()` method to locate the position of `@`.
3. Use string slicing to extract the characters before `@`.
4. Print the email, position of the symbol, and extracted username.

## 💻 Code

```python
email = "alice.johnson@company.com"

print(f"Email: {email}")

at_position = email.find("@")
print(f"Position of @: {at_position}")

username = email[:at_position]
print(f"Username: {username}")
```

## ▶️ Example Output

```text
Email: alice.johnson@company.com
Position of @: 13
Username: alice.johnson
```

## 🧠 Python Concepts Learned

- Variables and strings
- The `.find()` string method
- String indexing and slicing
- Printing output with f-strings

## 🚀 How to Run

1. Make sure Python 3 is installed.
2. Clone this repository or download the project files.
3. Open a terminal in the project directory.
4. Run the following command:

```bash
python3 main.py
```

## 🎯 Purpose

This project is part of my Python learning journey and helps me practice fundamental string manipulation techniques.

---

**Author:** Hashini Konara

*Learning Python one project at a time.* 🐍
