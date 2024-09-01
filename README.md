# Candidate Matching & Recruitment Optimization
# Excel to SQL Import Script

This script reads data from each sheet of an Excel file and imports it into a MySQL database.

## Features

- Reads an Excel file and processes each sheet.
- Formats column names by replacing spaces with underscores.
- Uploads data from each sheet to a MySQL database.
- Handles errors during the data upload process.

## Requirements

- Python 3.x
- pandas
- SQLAlchemy
- pymysql

## Setup

1. Install the required Python packages:
    ```bash
    pip install pandas sqlalchemy pymysql
    ```

2. Modify the script to include your own database connection string and file path.

## Usage

1. Update the `db_connection_str` with your MySQL database credentials.
2. Update the file path in `pd.ExcelFile` with the path to your Excel file.
3. Run the script:
    ```bash
    python your_script_name.py
    ```
