---

# Student Database Management System (Std_DBMS)

This is a simple Java console-based application for managing student records. It allows users to add new students, view a list of all students, search for a specific student, and calculate the average marks of all students in the database.

## Getting Started

To get started with the Student Database Management System, follow these steps:

### Prerequisites

- Java Development Kit (JDK) installed on your system

### Running the Program

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/student-dbms.git
   ```

2. Navigate to the project directory:
   ```bash
   cd student-dbms
   ```

3. Compile the Java program:
   ```bash
   javac Std_DBMS.java
   ```

4. Run the compiled program:
   ```bash
   java Std_DBMS
   ```

## Features

### 1. Add Student

Allows users to add a new student to the database by providing the student's name, roll number, age, and marks.

### 2. View Student

Displays a list of all students in the database along with their details, including name, roll number, age, and marks.

### 3. Search Student

Enables users to search for a specific student in the database by entering the student's roll number. If found, it displays the student's details.

### 4. Calculate Average Marks

Calculates and displays the average marks of all students in the database.

### 5. Exit

Allows users to exit the program.

## Usage

1. When the program starts, you will be presented with a menu of options.
2. Choose an option by entering the corresponding number and pressing Enter.
3. Follow the prompts to add, view, search, or calculate as needed.
4. To exit the program, choose option 5.

## Sample Code Explanation

The main functionality of the Student Database Management System is implemented in `Std_DBMS.java`. Here are some key components:

- `main(String[] args)`: The main method where the program execution begins. It presents the menu of options and handles user input using a `switch` statement.
- `addStudent()`: Adds a new student to the `database` HashMap.
- `viewStudents()`: Displays the details of all students in the `database`.
- `searchStudent(int roll)`: Searches for a student with the given roll number in the `database` and displays the details if found.
- `calculateAverageMarks()`: Calculates the average marks of all students in the `database`.

## Contributing

If you'd like to contribute to the Student Database Management System, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/my-feature`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/my-feature`)
6. Create a new Pull Request

We welcome contributions and feedback from the community!
---
