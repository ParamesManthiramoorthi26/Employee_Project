# Employee Database Project

This project loads an employee dataset into PostgreSQL and uses Python to query it.

## Files
- `employees_schema.sql` – SQL script to create schema
- `employee_dump.sql` – SQL dump with data
- `employee_query.py` – Python script to query database

## Setup

1. Create a PostgreSQL database named `employee_db`
2. Run:
    ```bash
    psql -d employee_db -f employee.schema.sql
    psql -d employee_db -f employee.dump.sql
    ```

3. Edit the `employee_query.py` file with your DB credentials.
4. Run the Python script:
    ```bash
    python employee_query.py
    ```
