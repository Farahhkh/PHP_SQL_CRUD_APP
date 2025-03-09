# CRUD Application in PHP

This is a simple CRUD (Create, Read, Update, Delete) application built using PHP and MySQL. The application allows you to manage student records, including adding new students, viewing all students, updating student information, and deleting student records.

## Project Structure

```
students.sql
crud_app/
    dbcon.php
    delete_page.php
    footer.php
    header.php
    index.php
    insert_data.php
    style.css
    update_page_1.php
```

## Files Description

- **students.sql**: SQL script to create the `students` table and insert sample data.
- **crud_app/dbcon.php**: Database connection file.
- **crud_app/delete_page.php**: Handles the deletion of student records.
- **crud_app/footer.php**: Footer HTML content.
- **crud_app/header.php**: Header HTML content.
- **crud_app/index.php**: Main page that displays all student records and provides options to add, update, and delete records.
- **crud_app/insert_data.php**: Handles the insertion of new student records.
- **crud_app/style.css**: CSS file for styling the application.
- **crud_app/update_page_1.php**: Handles the updating of student records.

## Setup Instructions

1. **Clone the repository**:
    ```sh
    git clone https://github.com/Farahhkh/PHP_SQL_CRUD_APP.git
    ```

2. **Import the database**:
    - Open your MySQL database management tool (e.g., phpMyAdmin).
    - Create a new database named `crud_operation`.
    - Import the students.sql file into the `crud_operation` database.

3. **Configure the database connection**:
    - Open dbcon.php.
    - Ensure the database connection details (hostname, username, password, database name) are correct.

4. **Run the application**:
    - Place the crud_app folder in your web server's root directory (e.g., `htdocs` for XAMPP).
    - Open your web browser and navigate to `http://localhost/crud_app/index.php`.

## Usage

- **View All Students**: The main page (`index.php`) displays all student records.
- **Add Student**: Click the "ADD STUDENTS" button to open a modal form and add a new student.
- **Update Student**: Click the "Update" button next to a student record to update the student's information.
- **Delete Student**: Click the "Delete" button next to a student record to delete the student.

## Dependencies

- PHP 7.4 or higher
- MySQL 5.7 or higher
- Bootstrap 5.3.3 (included via CDN)

## License

This project is licensed under the MIT License.

## Acknowledgements

- Bootstrap for the front-end framework.
- phpMyAdmin for database management.

Feel free to contribute to this project by submitting issues or pull requests. Enjoy managing your student records with this simple CRUD application!
