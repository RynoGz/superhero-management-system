# Superhero Management System

## Overview

This project is a Windows Forms application developed in C# for managing superhero data. The system allows users to create, view, update, and delete superhero records through a graphical user interface.
The application uses file-based storage to persist data and applies object-oriented programming principles to manage superhero information efficiently.


## Technologies Used

* C#
* .NET Windows Forms
* File Handling (Text Files)


## Features

### Superhero Management

* Add new superheroes
* Update existing superhero records
* Delete superheroes
* View all stored superheroes in a DataGridView

### Data Persistence

* Stores data in a text file (`superheroes.txt`)
* Reads and writes data using file handling

### Business Logic

* Automatically calculates:
  - Hero Rank (S, A, B, C)
  - Threat Level based on exam score

### Reporting

* Generates a summary report including:
  - Total superheroes
  - Average age
  - Average exam score
  - Number of heroes per rank
  - Saves report to a file (`summary.txt`)

### Input Validation

* Ensures valid data entry
* Prevents incorrect or incomplete input


## What I Learned

* Building desktop applications using Windows Forms
* Implementing full CRUD functionality
* Working with file-based data storage
* Applying object-oriented programming (OOP) principles
* Handling user input and validation in GUI applications


## Project Structure

* `src/` – application source code

  - `Form1.cs` – main application logic and UI handling
  - `Hero.cs` – superhero data model and logic
  - `Program.cs` – application entry point


## How to Run

1. Open the project in Visual Studio
2. Build the solution
3. Run the application
4. Use the interface to manage superhero data


## Contribution

This project was developed as part of a group assignment. I contributed to the design and implementation of the system alongside my team.
