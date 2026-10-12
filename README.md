# OS Lab 03 — Batch Scripting & Windows Automation

Batch (`.bat`) scripts for **Operating Systems Lab 03**: practicals, practice questions, the hands-on activity and the final lab task. The scripts cover folder creation, file creation with output redirection, variables, user input, arithmetic, `IF / ELSE`, file-existence checks and `FOR` loops.

## Requirements

- Microsoft Windows 10/11
- Command Prompt (CMD)

## Contents

All scripts are in the `OS3/` folder.

| File | Topic |
|------|-------|
| `Practical_1.bat` | Create folders: Lectures, Assignments, Backup |
| `Practical_2.bat` | Create the `Operating_Systems` folder structure and display it with `tree` |
| `Practical_3.bat` | Create a student information file using `>` and `>>` |
| `Practical_4.bat` | Take the user's name with `set /p` and display a welcome message |
| `Practical_5.bat` | Add two numbers using `set /a` |
| `Practical_6.bat` | Pass/Fail check using `IF / ELSE` |
| `Practical_7.bat` | Create `Student1`–`Student5` using a `FOR` loop |
| `Practical_8.bat` | Complete automation: input, folder, file, backup and display |
| `Question_1.bat` | Print a welcome message |
| `Question_2.bat` | Create the Windows, Linux and Backup folders |
| `Question_3.bat` | Create a folder from user input (quoted for names with spaces) |
| `Question_4.bat` | Check whether `assignment.txt` exists |
| `Question_5.bat` | Create `Week1`–`Week10` using `FOR /L` |
| `Problem_Solving_Report_Backup.bat` | Back up `report.txt` only if it exists |
| `Hands_On_Activity.bat` | Automatic lab workspace creator |
| `student_record.bat` | Lab task: automatic student record generator |

## How to Run

1. Download or clone the repository.
2. Copy the `OS3` folder to a safe test location, for example `C:\OSLabPractice`.
3. Double-click a `.bat` file, or run it from CMD:

```bat
cd C:\OSLabPractice\OS3
Practical_1.bat
```

Most scripts create folders and files in the folder they are run from. Running a script twice may show a "folder already exists" error from `mkdir`.

## Safety Note

These scripts only create folders and files, but batch files run quickly. Do not practise on `C:\Windows`, `C:\Program Files`, personal folders or network drives. Use a dedicated test directory.

## Concepts Covered

`@echo off` · `echo` · `pause` · `REM` · `set` · `set /p` · `set /a` · `if` · `if exist` · `if not exist` · `for` · `for /L` · `title` · `>` · `>>`
