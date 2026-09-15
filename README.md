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

<img width="1440" height="900" alt="File 1" src="https://github.com/user-attachments/assets/563891e1-e08f-4b1f-8e65-f48f28dc4521" />

---

<img width="1440" height="900" alt="File 2" src="https://github.com/user-attachments/assets/0aad1f6d-0f97-4ef4-974b-954b90ac4ab4" />

---

<img width="1440" height="900" alt="File 3" src="https://github.com/user-attachments/assets/9ec05bbb-7f05-45bd-88b1-667c48382c21" />

---

<img width="1440" height="900" alt="File 4" src="https://github.com/user-attachments/assets/2c4caefc-df2f-4141-83aa-d8752da89c15" />

---

<img width="1440" height="900" alt="File 5" src="https://github.com/user-attachments/assets/bbbb1326-640b-4758-a9e1-cd43c08f68bb" />

---

<img width="1440" height="900" alt="File 6" src="https://github.com/user-attachments/assets/3e50d263-a08f-4478-b1b8-9acf3f3031e2" />

---

<img width="1440" height="900" alt="File 7" src="https://github.com/user-attachments/assets/b6099e76-1415-42a3-8a55-cb74a88add50" />

------------------------------------------------------------------------------------

# 🖥️ Program Results / Output

<img width="1440" height="900" alt="File 8" src="https://github.com/user-attachments/assets/9869a14a-82f0-4dfb-85c5-14b9a7a402e1" />

---

<img width="1440" height="900" alt="File 9" src="https://github.com/user-attachments/assets/0f5c36f2-d58d-4338-9f9f-9e04e0e54e9a" />


------------------------------------------------------------------------------------
# 🎥 Project Explanation Video

A complete explanation of this project is available in the Google Drive video below.

### 🔗 Google Drive Link

https://drive.google.com/drive/folders/1rs8PXQPL6kIEc1gXxTx6czgLlZaNujtm?usp=sharing

---

# 📂 Project Structure

# 📂 Project Structure

```text
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
    ├── File 4.jpeg
    ├── File 5.jpeg
    ├── File 6.jpeg
    └── File 7.jpeg
```

### 📁 Files & Folders

* **`Project2.cpp`** — Main C++ source code of the Railway Reservation System.
* **`README.md`** — Project documentation, features, concepts, and project explanation.
* **`Screenshots/`** — Contains all screenshots related to the project.
* **`File 1.jpeg` – `File 7.jpeg`** — Screenshots of the source code and program execution/results.

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
