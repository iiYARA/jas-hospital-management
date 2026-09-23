# JAS · Hospital Management System

**C++ · Data structures · Console application**

A hospital simulation that connects data structures to practical tasks: storing patient records, prioritizing emergency cases, and undoing the most recent treatment entry.

[View the source](main.cpp) · [Project documentation](https://sites.google.com/view/jashospital/home)

## How it works

| Feature | Data structure | Behavior |
| --- | --- | --- |
| Patient records | Array + linked list | Stores the first 100 patients in an array, then additional patients in a linked list |
| Emergency handling | Priority queue | Processes patients according to the program's condition-based priority |
| Treatment history | Stack | Records treatments and removes the latest entry when undo is selected |

The menu supports adding, viewing, and deleting patients, handling emergencies, and recording or undoing treatments. Data is held in memory during the session.

## Run locally

With a C++11-compatible compiler or newer:

```bash
git clone https://github.com/iiYARA/jas-hospital-management.git
cd jas-hospital-management
g++ -std=c++11 main.cpp -o hospital
./hospital
```

On Windows, compile to `hospital.exe` and run `.\hospital.exe` in PowerShell.

## Team contributions

| Member | Contribution |
| --- | --- |
| Asma Alsakkaf | Array implementation and documentation portfolio edits |
| Judy Alimam | Linked lists, queue, and documentation portfolio |
| Yara Mohammad | Stack implementation and GitHub management |

## Course

Data Structures and Algorithms · Effat University  
Instructor: Dr. Naila Marir · Submitted April 30, 2025

This is an educational simulation; emergency priorities are simplified program rules.

