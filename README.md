Digital Attendance System

Overview

The **Digital Attendance System** is a beginner-level C++ project designed to help lecturers and students manage attendance efficiently. The system allows users to:

- Register students  
- View registered students  
- Create lecture sessions  
- Mark attendance (Present, Absent, Late)  
- Generate an automatic Microsoft Word-compatible attendance report  

The project was developed incrementally over **four weeks**, implementing object-oriented programming principles, file handling, and menu-driven console interface.

---

Features

1. Week 1 – Student Management
- `Student` class stores student index number, name, and program.  
- Register new students.  
- View all registered students.

2. Week 2 – Attendance Session Creation
- `AttendanceSession` class stores session details: course code, date, start time, duration.  
- Create lecture sessions linked to students.

3. Week 3 – Attendance Marking
- Prompt user to mark each student as **Present (P)**, **Absent (A)**, or **Late (L)**.  
- Display a summary of total present, absent, and late students.

4. Week 4 – File Handling & Microsoft Word Report
- Generate `Attendance_Report.doc` with all attendance details.  
- Automatically opens the report in Microsoft Word for editing, viewing, or printing.

---

How to Use

1. Open the project in a **C++ IDE** (Code::Blocks, Dev C++, Visual Studio).  
2. Compile and run `main.cpp`.  
3. Navigate the menu:
    1. Register Student  
    2. View Students  
    3. Create Lecture Session & Mark Attendance  
    4. Exit  
4. After marking attendance, `Attendance_Report.doc` will open automatically in Microsoft Word.


Requirements

- Windows operating system  
- Microsoft Word installed  
- C++ compiler (Code::Blocks, Dev C++, Visual Studio, etc.)

---
File Structure
