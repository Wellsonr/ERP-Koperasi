# ERP-Koperasi

Customize your GF Accounting Application with the following instructions to quickly set it up and get started.

## Getting Started

### 1. Download the Repository
To get started, clone the GitHub repository to your local machine using the command:
git clone https://github.com/Wellsonr/ERP-Koperasi.git

### 2. Database Initialization
Before using the application, set up the database:

- **Download MySQL Format**:
  - Access the MySQL database file inside the `requirement` folder.
- **Restore the Database**:
  - Set to Ignore Errors
  - Import the MySQL file into your DBMS to restore the database.
- **Set Up Database**:
  - Choose the database that u just restore: 'set database ur_db_name; '
  - Set Allowed Package in the database using query: 'SET GLOBAL max_allowed_packet=16777216; '
 
### 3. Application Setup
Configure the application to ensure it can connect to your database:

- **Configure GF.exe.config**:
  - Navigate to `invetory.exe.config` within the cloned repository.
  - Search for `SetUp Database` and enter your database details, including password if required.

### 4. Account Information
Login to the application using the default user credentials:

- **Username:** ADMINISTRATOR
- **Password:** 123

## Sneak Peek
Here are some screenshots of the ERP-Koperasi Application:


## Warning
This project not for any commercial use.
