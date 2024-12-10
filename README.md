# Library Management System

The **Library Management System** is a desktop application built using **PyQt5** for managing a library's books, clients, authors, and borrowing operations. It also includes a dashboard for visualizing borrowing trends and client activity using **Matplotlib** and **Plotly**.

## Features

### 1. User Authentication
- Login system for verifying user credentials.
- Admin users can manage the library's database.

### 2. Book Management
- Add, edit, delete, and search books.
- Export books data to Excel files.

### 3. Client Management
- Add, edit, delete, and search clients.
- Export client data to Excel files.

### 4. Borrowing Operations
- Manage day-to-day borrowing operations.
- Track borrowing and return dates for books.

### 5. Dashboard Analytics
- Visualizations for:
  - Borrowed Books Summary
  - Category Popularity
  - Borrowing Trends (Monthly Trends)
  - Client Activity Summary
- Interactive filtering and date-range-based visualization.

### 6. Theme Support
- Dark Blue Theme
- Dark Gray Theme
- Dark Orange Theme
- QDark Theme

## Technologies Used

- **Python**: Core programming language.
- **PyQt5**: GUI framework.
- **Matplotlib**: For creating visualizations in the dashboard.
- **Plotly**: Interactive visualizations.
- **MySQL**: Database for managing library data.
- **XlsxWriter**: Exporting data to Excel files.
- **Datetime**: Managing date operations.

## Setup and Installation

### Prerequisites
- Python 3.7 or higher installed.
- MySQL Server installed and configured.
- Required Python libraries installed.

### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/shashidharbabu/library-management.git
   cd library-management
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up the MySQL database:
   - Create a database named `library_management`.
   - Import the SQL schema and data from the `database_schema.sql` file.

4. Run the application:
   ```bash
   python app.py
   ```

## File Structure

```
.
├── app.py                 # Main application file
├── new_library.ui         # UI file for the main application
├── login.ui               # UI file for the login screen
├── themes/                # Directory containing theme CSS files
│   ├── darkblue.css
│   ├── darkgray.css
│   ├── darkorange.css
│   ├── qdark.css
├── database_schema.sql    # SQL file for database schema and initial data
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
└── charts/                # Visualization helper files
```

## Screenshots

### Dashboard Overview
### Book Management
### Client Management
