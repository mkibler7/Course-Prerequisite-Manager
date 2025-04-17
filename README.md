# Course Prerequisite Manager

A C++ console application designed to help students and advisors manage university course planning. Built with a custom hash table, this tool loads course data from a CSV file, validates prerequisites, and presents a user-friendly menu to view and interact with course schedules.

## Features

- ✅ Load and parse course data from CSV
- ✅ Validate and ignore invalid prerequisites
- ✅ Store all courses in a custom hash table
- ✅ Print an alphanumerically sorted list of courses
- ✅ Display course details including prerequisites
- ✅ Menu-driven console UI


## Tech Stack

- **C++** – Core development language
- **Visual Studio 2022** – Development environment
- **Standard Template Library (STL)** – Data structures and file I/O
- **Custom Hash Table** – Implemented with chaining
- **CSV File Parsing** – For loading course and prerequisite data

## What I Learned

- Mobile app lifecycle management
- Building and styling Android UI with XML
- Handling user input, form validation, and intent-based navigation
- Working with SQLite databases for persistent storage
- Writing modular, maintainable Java code using MVC architecture

## Screenshots

![image](https://github.com/user-attachments/assets/72738f5a-55ba-453f-9bff-13e511375eda)
![image](https://github.com/user-attachments/assets/5449002b-d5de-46fe-81ec-54933ebe7b4a)
![image](https://github.com/user-attachments/assets/997224d1-3c40-4418-9842-6df87ec84d70)

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/CoursePrerequisiteManager.git
   ```
2. Open `ProjectTwo.sln` in Visual Studio  
3. Build the solution  
4. Run the program  
5. When prompted, enter:
   ```
   CS_300_ABCU_Advising_Program_Input.csv
   ```
   
## Sample CSV Format

```csv
CS101,Introduction to Programming
CS102,Data Structures,CS101
CS103,Algorithms,CS102
```

Each row includes:  
`CourseNumber, CourseTitle, [Prerequisite1, Prerequisite2, ...]`

## Academic Context
This project was developed for the final assignment in:

- **Course:** CS 300: Data Structures and Algorithms  
- **Institution:** Southern New Hampshire University  
- **Date Completed:** August 2024


## Author/Contact Info

Created by **Michael Kibler**  
[LinkedIn](https://www.linkedin.com/in/michael-kibler-11369519b/) | [Email](mailto:mpkibler7@gmail.com)
