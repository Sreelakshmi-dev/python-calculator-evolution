# Level10_Event_Driven_Calculator
# Python Calculator — Level 10 | Tkinter GUI

Level 10 focuses on transforming a basic GUI calculator into a more interactive and structured desktop application using Python's Tkinter library.

This version brings together **Object-Oriented Programming (OOP), event-driven programming, application state management, keyboard interaction, memory operations, and file handling**.

The calculator supports continuous arithmetic operations, memory storage and retrieval, calculation history, and keyboard input. It also includes input validation and exception handling to improve reliability.

### Key Features

- **Interactive GUI:** A Tkinter-based calculator with a dark theme, custom-styled buttons, and a read-only display.
- **Keyboard Support:** Handles numeric input, arithmetic operators, Enter, and Backspace using keyboard event bindings.
- **Continuous Calculations:** Allows users to perform consecutive operations without manually clearing previous results.
- **Memory Management:** Supports saving, recalling, and deleting stored calculation results using M, MR, and MD.
- **Calculation History:** Records calculations in CSV format and provides a separate history viewer.
- **Input Validation:** Handles leading zeros, decimal points, incomplete operands, and backspace operations.
- **Error Handling:** Uses exception handling to manage division by zero and display an appropriate message.

### Python Concepts Applied

**1. Object-Oriented Programming (OOP)**
- Classes and objects
- Constructors (`__init__`)
- Instance attributes and methods
- Encapsulation
- Abstraction and abstract classes
- Inheritance and polymorphism

**2. Event-Driven Programming**
- Tkinter's event loop
- Button commands and callbacks
- Keyboard bindings using `bind()`
- Event handling using `event.char` and `event.keysym`
- Lambda expressions

**3. Application State Management**
- Tracking operands, operators, and calculation results
- State flags for managing user input
- Managing memory recall and history window states
- Resetting calculation states after clearing or errors

**4. Error Handling and Input Validation**
- `try` and `except`
- `ZeroDivisionError`
- Conditional statements
- Type conversion using `int()` and `float()`
- Decimal-point validation

**5. File Handling and Modular Programming**
- Working with CSV files
- Recording calculation history
- Separating GUI, arithmetic operations, and history management into individual Python modules
- Importing and reusing custom modules

### Project Structure

```text
main.py
calculator_abstract_class.py
tkinter_csv.py
```

### Learning Outcome

Level 10 demonstrates how individual Python concepts can work together to build a functional desktop application.

The main focus is on **handling user interactions, maintaining application state, integrating OOP with Tkinter, and managing calculations reliably**.

This project is part of a progressive Python Calculator series, developed step by step from fundamental programming concepts toward more advanced application development.
## Level 10 — Known Limitations & Future Improvements

Although Level 10 introduces event-driven programming, keyboard support, application state management and improved calculation handling, some limitations remain.

1. **Left-to-Right Evaluation:** Continuous calculations are evaluated in the order entered rather than following standard mathematical operator precedence (BODMAS).

2. **Limited Mathematical Operations:** The calculator currently supports basic arithmetic and modulo operations. Advanced functions such as square roots, powers and trigonometric calculations are not included.

3. **Fixed Window Size:** The calculator uses a fixed window size of 230 × 315 pixels and cannot be resized.

4. **Single Memory Value:** The memory feature stores one result at a time rather than supporting multiple stored values.

### Future Improvements

These limitations provide opportunities to explore more advanced concepts in future calculator levels, including improved numerical precision, expression parsing, flexible GUI layouts and expanded mathematical functionality.
### Level 11 Roadmap — Scientific Calculator

Level 11 will focus on upgrading the existing Tkinter GUI calculator into a scientific calculator by integrating Python's `math`, NumPy, and Matplotlib libraries.

This level will introduce advanced mathematical operations, trigonometric functions, logarithms, powers, square roots, and mathematical expression parsing with operator precedence.

Matplotlib will be integrated with Tkinter to visualise mathematical functions through interactive graphs, including linear, quadratic, and trigonometric functions.

**Key Programming Concepts:**
- Scientific computing using `math` and NumPy
- Mathematical expression parsing and operator precedence
- Advanced Object-Oriented Programming (OOP)
- Data visualisation using Matplotlib
- Integrating graphs into Tkinter
- Advanced exception handling and input validation

**Learning Goal:** To develop a scientific calculator that combines mathematical computation, expression evaluation, and graphical visualisation while improving the application's architecture and functionality.

#Output Samples
#1.Calculation sample
<img width="960" height="540" alt="calculation_sample" src="https://github.com/user-attachments/assets/04190c48-53fc-43b2-b8f7-1437f32a816f" />

#2.Undefined sample-Error handling
<img width="960" height="540" alt="Undefined" src="https://github.com/user-attachments/assets/8c7addcd-42a7-4246-990b-12d5564681e2" />

#3.History_view
<img width="960" height="540" alt="history_view" src="https://github.com/user-attachments/assets/fca317f6-b0b9-42ba-9d16-5243a20abd27" />

#4.csv_open_sample
<img width="960" height="540" alt="csv_open_sample" src="https://github.com/user-attachments/assets/0024a835-879b-46a5-92ca-9792304d0484" />

#5.CSV_sample_output
<img width="960" height="540" alt="csv_sample_output" src="https://github.com/user-attachments/assets/371f5892-f3e7-4045-8e9c-877831478cf4" />

#Output video sample


https://github.com/user-attachments/assets/d85f0982-d522-4ac9-8753-a2104e6ee2ea


What would you improve?

