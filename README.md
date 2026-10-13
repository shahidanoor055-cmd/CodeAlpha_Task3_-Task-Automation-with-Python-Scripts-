# JPG File Organizer Using Python

## Project Overview

The JPG File Organizer is a simple Python automation project that moves all `.jpg` images from a source folder to a destination folder. It automates repetitive file management and helps keep files organized.

## Features

- Automatically identifies `.jpg` files in a folder.
- Creates the destination folder if it does not exist.
- Moves JPG files to the destination folder.
- Displays the names of moved files.
- Supports uppercase and lowercase JPG extensions.

## Technologies Used

- Python
- `os` module
- `shutil` module

## Project Structure

```text
Task3_FileOrganizer/
│
├── file_organizer.py
├── images/
│   └── sample.jpg
└── organized_images/
```

The `images` folder contains the source images. The `organized_images` folder is created automatically when the program runs.

## Installation and Execution

1. Install Python on your computer.
2. Create a project folder named `Task3_FileOrganizer`.
3. Create an `images` folder inside the project folder and add JPG images.
4. Save the Python code as `file_organizer.py`.
5. Open a terminal in the project folder.
6. Run the following command:

```bash
python file_organizer.py
```

## How It Works

1. The program checks whether the destination folder exists.
2. If the folder does not exist, it creates it.
3. It checks each item in the source folder.
4. It identifies JPG files and moves them to the destination folder.
5. It displays a completion message.

## Learning Outcomes

- Understanding file and folder handling in Python.
- Using the `os` module to manage directories and files.
- Using the `shutil` module to move files.
- Applying loops and conditional statements.
- Automating repetitive tasks with Python scripts.

## Internship Information

**Organization:** CodeAlpha  
**Internship:** Python Programming Internship  
**Task:** Task 3 — Task Automation with Python Scripts

## Project Purpose

This project demonstrates how Python can automate everyday file-management tasks, reduce manual effort, and improve efficiency.
