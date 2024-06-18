# JDBC Employee Management

This is a simple Java program for managing employee records using JDBC (Java Database Connectivity) with a MySQL database.

## Features

- Create new employee records
- Read existing employee records
- Update employee records
- Delete employee records

## Requirements

- Java Development Kit (JDK)
- MySQL Server
- MySQL JDBC Driver

## Setup

1. **Database Setup**: 
    - Install and setup MySQL Server.
    - Create a database named `LearningJDBC`.
    - Create a table named `employee` with columns: `eid` (INT, Auto Increment), `fullname` (VARCHAR), `salary` (DOUBLE), `jobTitle` (VARCHAR), `residentialArea` (VARCHAR).
    ```sql
    CREATE TABLE employee (
        eid INT PRIMARY KEY AUTO_INCREMENT,
        fullname VARCHAR(100) NOT NULL,
        salary DECIMAL(10,2),
        jobTitle VARCHAR(100),
        residentialArea VARCHAR(50)
    );
    ```

2. **JDBC Driver**: 
    - Download the MySQL JDBC Driver (usually a JAR file) from the official MySQL website or Maven repository.
    - Add the JDBC driver JAR file to your project's classpath.

3. **Downloading the Program**:
    - Clone this repository to your local machine using Git.
    ```
    git clone https://github.com/meghshamkapure/jdbc-employee-management-using-statement-interface
    ```
    Or download the ZIP file and extract it to a directory on your computer.

4. **Compilation**: 
    - Navigate to the directory where the `JDBCEmployeeAppCRUD.java` file is located.
    - Compile the Java file using the Java compiler.
    ```
    javac JDBCEmployeeAppCRUD.java
    ```

5. **Execution**: 
    - Run the compiled program.
    ```
    java JDBCEmployeeAppCRUD
    ```

## Usage

- Upon running the program, you'll be presented with a menu to perform CRUD operations on employee records.
- Follow the prompts to create, read, update, or delete employee records as needed.

## Author

- Name: Meghsham Suresh Gaonkar
- Phone: +91 70663 26068
- Email: mail.meghsham@gmail.com

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
