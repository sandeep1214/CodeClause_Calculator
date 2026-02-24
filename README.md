# 🧮 Simple Calculator (Tkinter)

This project is a **basic calculator application** built using Python’s **Tkinter** GUI library.  
It supports simple arithmetic operations including addition, subtraction, multiplication, and division.

---

## 🚀 Features

- Clean and simple GUI  
- Supports:
  - Addition (`+`)
  - Subtraction (`-`)
  - Multiplication (`*`)
  - Division (`/`)
- Decimal support  
- Clear button  
- Error handling (shows **UNDEFINED** on invalid expressions)  
- Window auto-centers on startup  

---

## 🛠 Requirements

- Python 3.x  
- Tkinter (comes with most Python installations)

---

## ▶️ How to Run

1. Save the script as **calculator.py**
2. Open a terminal and run:
`python calculator.py`

The calculator window will open.

## 📂 Project Structure
```
calculator.py   # Main Tkinter calculator script
README.md       # Documentation
```
## 🧱 Code Overview

- fCalc() – Creates framed sections of the UI
- button() – Generates calculator buttons
- app class – Builds window layout, input display, and button arrangement
- result() – Evaluates the expression using eval() and handles errors
### Button layout:
```
7  8  9  /
4  5  6  *
1  2  3  -
0  .  +
```
The = button evaluates the displayed expression.

## 📸 Screenshot (Optional)

Add a screenshot here if you want, e.g.:
```
![Calculator Screenshot](screenshot.png)
```

