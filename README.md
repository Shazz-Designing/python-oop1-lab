# 📚 Object Oriented Programming Lab – Bookstore

## 📖 Overview

This lab demonstrates the use of Object-Oriented Programming (OOP) principles in Python by modeling a simple bookstore system.

Two classes were implemented:

- `Book`
- `Coffee`

The project focuses on:
- Class creation
- Object initialization
- Properties and validation
- Instance methods
- Test-driven development using Pytest
- Git workflow and version control

---

## 🧠 The Scenario

You are tasked with building two different classes to represent and model a bookstore.

- A **Book** object that allows a user to read an online book.
- A **Coffee** object representing a beverage sold in the store.

Each object contains attributes and methods that define its behavior.

---

## ⚙️ Setup Instructions

### 1️⃣ Fork and Clone
- Fork the GitHub repository to your account.
- Clone your fork locally.

### 2️⃣ Install Dependencies

```bash
pipenv install
pipenv shell
```

### 3️⃣ Run Tests

```bash
pytest -x
```

This project is test-driven. All tests must pass before submission.

You can run specific test files:

```bash
pytest -x testing/book_test.py
pytest -x testing/coffee_test.py
```

---

## 🏗️ Implementation Details

### 📘 Book Class

**File:** `lib/book.py`

#### Attributes:
- `title`
- `page_count`
  - Must be an integer
  - If not, prints:
    ```
    page_count must be an integer
    ```

#### Methods:
- `turn_page()`
  - Prints:
    ```
    Flipping the page...wow, you read fast!
    ```

---

### ☕ Coffee Class

**File:** `lib/coffee.py`

#### Attributes:
- `size`
  - Must be `"Small"`, `"Medium"`, or `"Large"`
  - If not, prints:
    ```
    size must be Small, Medium, or Large
    ```
- `price`

#### Methods:
- `tip()`
  - Prints:
    ```
    This coffee is great, here’s a tip!
    ```
  - Increases the coffee price by 1

---

## 🧪 Test-Driven Development

This project was built using a test-driven development approach:

- Run tests
- Fix one failure at a time
- Repeat until all tests pass

### ✅ Final Test Results

```
7 passed
```

*(Add screenshot below)*

---

## 📸 Screenshot

Add a screenshot of your passing tests below:

```markdown
![Passing Tests](tests_passed.png)
```

---

## 🛠️ Technologies Used

- Python
- Pipenv
- Pytest
- Git & GitHub

---

## 👩‍💻 Author

Sharon Apot