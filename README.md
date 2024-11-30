# Library Management System

A comprehensive Library Management System developed using Python (PyQt5), MySQL, and Matplotlib. This application helps manage books, clients, and borrowing records and provides insightful visualizations for librarians and administrators.

## Features

- **User Login System**: Secure login feature for librarians to access the system.
- **Book Management**: Add, edit, delete, and search for books.
- **Client Management**: Add, edit, delete, and search for clients.
- **Day Operations**: Borrowing and returning books is easy with records automatically maintained.
- **Export Data**: Export records of books, clients, and borrowing operations to Excel files for reporting purposes.
- **Data Visualizations**: Dashboards for insights, including:
  - Borrowed Books Summary
  - Category Popularity
  - Borrowing Trends
  - Client Activity Summary
- **Theming Support**: Multiple themes, including dark orange, blue, gray, and QDark themes.

## Visualizations Included

1. **Borrowed Books Summary**: Bar chart showing the total number of borrows per book.
2. **Category Popularity**: Pie chart representing the popularity of book categories.
3. **Borrowing Trends**: Line chart visualizing monthly borrowing trends.
4. **Client Activity Summary**: Bar chart displaying total books borrowed by clients.

## Installation

1. **Clone the Repository**:
   ```sh
   git clone <repository-url>
   ```

2. **Install Dependencies**:
   Install the required Python packages using `pip`:
   ```sh
   pip install PyQt5 mysql-connector-python matplotlib xlrd xlsxwriter
   ```

3. **Set Up Database**:
   - Create a MySQL database named `library_management`.
   - Import the `library_management.sql` file provided in the repository to set up the tables.

4. **Run the Application**:
   ```sh
   python main.py
   ```

## Usage

- **Login**: Use the login screen to access the main application.
- **Navigation**: Use the left-side buttons to navigate between different sections (books, clients, settings, operations).
- **Dashboard**: Click the last button on the left-side menu to view the analytics dashboard with visualizations.

## Project Structure

- `main.py`: Main entry point for the application.
- `new_library.ui`: UI file created using Qt Designer.
- `login.ui`: UI file for the login screen.
- `themes/`: Directory containing the CSS theme files.
- `day_operations.xlsx`, `all_books.xlsx`, `all_clients.xlsx`: Generated reports.

## Future Enhancements

- Add more visualizations for improved insights.
- Implement role-based access for different types of users (e.g., admin, staff).
- Integrate email notifications for clients when books are due.
---

