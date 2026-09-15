# 🚆 Railway Reservation System — C++ Project

## 📌 Project Overview

**Railway Reservation System** is a C++ console-based project designed to manage train records.

The program allows the user to:

1. **Add a new train record**
2. **Display all train records**
3. **Search for a train using its train number**
4. **Exit the system**

The project demonstrates important C++ concepts including **classes, objects, constructors, destructor, encapsulation, static members, arrays, functions, loops, switch-case, and searching**.

---

## 👨‍💻 Student Information

| Information      | Details                    |
| ---------------- | -------------------------- |
| **Name**         | Vansh Soni                 |
| **Language**     | C++                        |
| **Project Name** | Railway Reservation System |
| **Project Type** | Console Application        |

---

## ⚙️ Features

* Add new train records.
* Store train number, train name, source, destination, and train time.
* Display all stored train records.
* Search for a train using its train number.
* Supports up to **100 train records**.
* Handles invalid menu choices.
* Uses a menu-driven interface.
* Keeps track of Train objects using a static member.

---

## 🧠 Concepts Used

* `#include <iostream>`
* `#include <cstring>`
* Classes and Objects
* Private and Public Access Specifiers
* Default Constructor
* Parameterized Constructor
* Destructor
* Encapsulation
* Getters and Setters
* Static Data Member
* Character Arrays
* `strcpy()`
* `cin` and `cout`
* `getline()`
* Arrays of Objects
* `for` Loop
* `do-while` Loop
* `switch-case`
* Boolean Variable
* Searching

---

## 🏗️ Class Structure

### `Train` Class

The `Train` class stores information about an individual train.

It contains:

```text
Train Number
Train Name
Source
Destination
Train Time
```

The class also contains constructors, a destructor, setters, getters, input functions, and display functions.

---

### `RailwaySystem` Class

The `RailwaySystem` class manages multiple train records.

It stores up to **100 Train objects** using an array and keeps track of the total number of trains.

It provides functions for:

* Adding trains
* Displaying all trains
* Searching trains by number

---

## 🔄 How the Program Works

When the program starts, a `RailwaySystem` object is created.

A menu is displayed with four options:

```text
--- Railway Reservation System Menu ---

1. Add New Train Record
2. Display All Train Records
3. Search Train by Number
4. Exit
```

The user selects an option, and the `switch-case` statement calls the appropriate function.

### Option 1 — Add Train

The program takes the train number, train name, source, destination, and train time from the user and stores the information in the Train array.

### Option 2 — Display Trains

The program uses a `for` loop to go through all stored train records and displays their details.

### Option 3 — Search Train

The user enters a train number.

The program checks each stored train using a `for` loop. If the train number matches, the train details are displayed. Otherwise, it displays that the train was not found.

### Option 4 — Exit

The program displays an exit message and terminates the menu loop.

---

# 💻 Source Code

## Code Screenshot

> **Insert your C++ source-code screenshot here.**

```text
┌──────────────────────────────────────────────────────────────┐
│                                                              │
│                  PASTE CODE SCREENSHOT HERE                  │
│                                                              │
│                                                              │
│                                                              │
│                                                              │
│                                                              │
└──────────────────────────────────────────────────────────────┘
```

---

# 🖥️ Program Results / Output

## Result Screenshot 1 — Add Train

> **Insert screenshot showing a train record being added here.**

```text
┌──────────────────────────────────────────────────────────────┐
│                                                              │
│                PASTE RESULT SCREENSHOT HERE                  │
│                                                              │
│                                                              │
│                                                              │
└──────────────────────────────────────────────────────────────┘
```

---

## Result Screenshot 2 — Display Train Records

> **Insert screenshot showing all train records here.**

```text
┌──────────────────────────────────────────────────────────────┐
│                                                              │
│                PASTE RESULT SCREENSHOT HERE                  │
│                                                              │
│                                                              │
│                                                              │
└──────────────────────────────────────────────────────────────┘
```

---

## Result Screenshot 3 — Search Train

> **Insert screenshot showing the train search result here.**

```text
┌──────────────────────────────────────────────────────────────┐
│                                                              │
│                PASTE RESULT SCREENSHOT HERE                  │
│                                                              │
│                                                              │
│                                                              │
└──────────────────────────────────────────────────────────────┘
```

---

## Result Screenshot 4 — Exit / Invalid Choice

> **Insert another output screenshot here if required.**

```text
┌──────────────────────────────────────────────────────────────┐
│                                                              │
│                PASTE RESULT SCREENSHOT HERE                  │
│                                                              │
│                                                              │
│                                                              │
└──────────────────────────────────────────────────────────────┘
```

---

# 🎥 Project Explanation Video

A complete explanation of this project is available in the Google Drive video below.

### 🔗 Google Drive Link

https://drive.google.com/drive/folders/1rs8PXQPL6kIEc1gXxTx6czgLlZaNujtm?usp=sharing

---

# 📂 Project Structure

# 📂 Project Structure

```text
Railway-Reservation-System/
│
├── README.md
├── Project2.cpp
│
└── Screenshots/
    ├── File 1.jpeg
    ├── File 2.jpeg
    ├── File 3.jpeg
    └── File 4.jpeg
```

### 📁 Files & Folders

* **`Project2.cpp`** — Main C++ source code of the Railway Reservation System.
* **`README.md`** — Project documentation and explanation.
* **`Screenshots/`** — Contains screenshots of the source code and program outputs/results.
* **`File 1.jpeg – File 4.jpeg`** — Project screenshots showing the code and execution results.

```

---

# ▶️ How to Run

### Step 1

Open `Project2.cpp` in a C++ IDE or compiler.

### Step 2

Compile the program.

### Step 3

Run the program.

### Step 4

Select an option from the Railway Reservation System menu.

### Step 5

Enter the required information and view the result.

---

# ✅ Conclusion

This project is a simple **Railway Reservation System implemented in C++**.

It demonstrates the practical use of **object-oriented programming concepts**, along with functions, arrays, constructors, destructor, encapsulation, loops, switch-case, and searching.

---

# 🙏 Thank You

**Thank you for viewing my project!**

### Created by

**Vansh Soni**
