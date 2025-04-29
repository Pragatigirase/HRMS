# Human Resource Management System (HRMS)

A comprehensive web-based HRMS solution for managing employee information, attendance, leave requests, and more.

# Features

- **Employee Management:** Centralized system to manage employee profiles and departmental information
- **Attendance Tracking:** Record and monitor employee check-ins, check-outs, and breaks
- **Leave Management:** Streamline leave application and approval processes
- **Reporting:** Generate attendance and leave reports for better HR decision-making

## Technical Stack

- **Backend:** Flask (Python)
- **Database:** SQLite, MySQL 
- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Authentication:** Flask-Login

# Database Configuration

The application supports both SQLite and MySQL databases:

## SQLite 

The application uses SQLite by default, which requires no additional configuration.

# MySQL 

To use MySQL instead of SQLite:

1. Make sure MySQL server is installed and running
2. Run the MySQL setup script to create the database:


python setup_mysql.py


3. Set the required environment variables:


# Linux
export USE_MYSQL=1
export MYSQL_USER=root 
export MYSQL_PASSWORD=your_password  
export MYSQL_HOST=localhost  
export MYSQL_DB=hrms_db 

# Windows
set USE_MYSQL=1
set MYSQL_USER=root
set MYSQL_PASSWORD=your_password
set MYSQL_HOST=localhost
set MYSQL_DB=hrms_db


4. Restart the application

# Installation

1. Clone the repository
2. Install dependencies:


pip install -r requirements.txt


3. Run the application:


python run.py


# Default Admin Credentials

- **Username:** admin
- **Password:** admin123
