# PyTest REST API Demo

A simple `pytest` demo project that tests CRUD operations on a RESTful TODO API (`https://todo.pixegami.io`) using Python `requests`.  
It covers creating, reading, updating, listing, and deleting tasks.

---

## 📦 Project Structure

- `test_*.py` — contains pytest test cases.
- Uses `requests` for HTTP calls.

---

## ▶️ How to Run the Tests

Make sure you have `pytest` and `requests` installed:
```bash
pip install pytest requests
```

## Run all tests
```bash
pytest
```

## Run all tests with verbose output
```bash
pytest -v
```

## Run all tests with verbose output and see print statements
```bash
pytest -v -s
```

## Run a specific test only
For example, to run the test_can_create_task function:
```bash
pytest -v -s -k test_can_create_task
```
