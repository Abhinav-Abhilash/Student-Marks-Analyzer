# Student Marks Analyzer (Mini project 2)

A simple C++ console program to manage student records, validate marks, and display pass/fail results.

## Project Structure
- `miniproject-2.cpp` - Complete C++ source code containing the `Student` class and `main` function.
- `README.md` - Compilation and execution instructions.

## Prerequisites
- A C++ compiler (such as GCC/MinGW `g++`).

## Compilation and Execution

### On Windows (using MinGW / g++)
1. Open Command Prompt or PowerShell in this directory.
2. Compile the source code:
   ```cmd
   g++ miniproject-2.cpp -o student_analyzer.exe
   ```
3. Run the executable:
   ```cmd
   .\student_analyzer.exe
   ```

### On Linux / macOS (using g++)
1. Open a terminal in this directory.
2. Compile the source code:
   ```bash
   g++ miniproject-2.cpp -o student_analyzer
   ```
3. Run the executable:
   ```bash
   ./student_analyzer
   ```

## Sample Output
```text
Invalid marks for Rohan, set to 0

STUDENT DETAILS
Roll No | Name | Marks
101 | Nikhil | 88
102 | Meenu | 34
103 | Rohan | 0

Re-evaluation of Student 102

FINAL RESULTS
Roll No: 101
Name: Nikhil
Marks: 88
Result: Pass

Roll No: 102
Name: Meenu
Marks: 46
Result: Pass

Roll No: 103
Name: Rohan
Marks: 0
Result: Fail
```
