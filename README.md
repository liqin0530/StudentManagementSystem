This is a Python-based Student Management System developed as part of a university assignment. It is a terminal-based application that simulates essential academic features such as:

- Assignment management
- Timetable management
- Attendance tracking

## Features

### For Students:
- Submit and check assignment status
- Mark attendance using check-in codes
- Manage personal timetable (add, update, delete entries)
- View attendance percentages and weekly schedule

### For Lecturers:
- Generate 15-minute valid check-in codes for attendance
- View student attendance by course

## File Structure

- `assignments_StudentID.txt` — Stores assignment details
- `attendance_StudentID.txt` — Records student attendance
- `timetables_StudentID.txt` — Stores timetable information

## Technologies Used

- Python 3
- `tkinter` (for file dialogs)
- ANSI color codes (for terminal formatting)

## Note

This project was created for academic purposes and is not used in production. Data is stored in `.txt` files and there is no database integration.
