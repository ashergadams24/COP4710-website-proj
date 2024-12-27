# Theory of Databases Final Project

## Overview
This repository contains the project files for the COP4710 Theory of Databases course at FSU. It features a real estate database implemented in SQL and a PHP interface for interacting with the database.

### Project Components
- `schema.sql`: Contains all SQL commands for setting up the database schema including table creation.
- `queries.sql`: Includes SQL queries that can be run on the server where the database is hosted, demonstrating various data manipulations and retrievals.
- `onefilephp.php`: A PHP script that provides a web interface to interact with the database, allowing users to execute predefined queries and input custom SQL commands.

## How to Run
### Database Setup
1. Start SQL server and ensure it is running
2. Create the database by logging in and running `schema.sql` or copying the code from it.
3. Test if it works by running `SELECT * FROM (any table)`
4. Run `queries.sql` or copy and paste the code from it to view table data

### Web Interface Setup
1. Place `onefilephp.php` in your web server's root directory
2. Configure connection
3. Access the file through your web browser by visiting `http://localhost/onefilephp.php`

### Usage
- Run queries by selecting them on the web interface
- Input custom queries in the provided form field to interact with database directly

## Contributors
- Asher Adams
- Kevin Sturge
