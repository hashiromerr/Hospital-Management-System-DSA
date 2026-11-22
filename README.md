# Hospital Management System

### A Data Structures and Algorithms Project Using C++

A Hospital Management System developed using **C++**, **HTML**, **CSS**, and **JavaScript**. The project demonstrates how fundamental data structures and algorithms can be applied to manage patient records and hospital appointments through an interactive web-based interface.

The application integrates a C++ backend with a modern frontend, allowing users to register patients, manage medical records, schedule appointments, and monitor hospital activities.

## Project Overview

The Hospital Management System was developed as part of the **Data Structures and Algorithms (DSA) Open-Ended Lab**.

Its primary objective is to demonstrate the practical implementation of data structures and algorithms in a real-world management scenario.

Rather than relying on advanced STL containers, the system uses manually implemented linked structures to manage patient information and appointment records.

### Key Objectives

- Implement fundamental data structures using C++.
- Perform patient registration, searching, updating, and deletion.
- Apply searching and sorting algorithms to patient records.
- Implement queue-based appointment scheduling.
- Manage appointment statuses.
- Integrate C++ backend functionality with a web-based frontend.
- Handle invalid inputs and boundary conditions.

---

## Technologies Used

| Technology | Purpose |
|---|---|
| C++ | Core backend logic and data structures |
| HTML5 | Frontend structure |
| CSS3 | User interface design and responsive styling |
| JavaScript | Frontend functionality and API communication |
| cpp-httplib | HTTP server and API endpoints |
| Git & GitHub | Version control and source-code management |
| Visual Studio Code | Development environment |

---

## Core Features

### 1. Patient Management

The system provides a complete set of patient record management operations.

**Patient Registration**
- Register new patients with a unique ID.
- Store patient name, age, and medical condition.
- Reject duplicate patient IDs.
- Validate patient information before registration.

**Patient Searching**
- Search for patients using their unique IDs.
- Retrieve patient information through linear search.
- Display matching records in the frontend.

**Patient Record Updating**
- Modify an existing patient's name, age, or medical condition.
- Locate records using their unique patient IDs.

**Patient Deletion**
- Remove patient records from the linked list.
- Update linked-list connections after deletion.
- Handle attempts to delete nonexistent records.

**Patient Sorting**
- Arrange patient records in ascending order of patient ID.
- Implement Bubble Sort manually in C++.

### 2. Appointment Management

The system uses a linked queue structure to organize appointments.

**Appointment Scheduling**
- Schedule appointments for registered patients.
- Assign a unique appointment ID.
- Store the doctor's name and appointment date.
- Add
