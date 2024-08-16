
# Data Processing and Database Ingestion

## Overview
This repository contains a Jupyter Notebook that demonstrates the process of loading, cleaning, and storing data into a MySQL database. The notebook is designed to process data from Excel files, perform necessary cleaning operations, and insert the cleaned data into the database.

## Process Details

### 1. Loading Data
- The notebook loads data from Excel files into pandas DataFrames.
- The data files include exchange rates and customer details.

### 2. Data Cleaning
- Cleaning operations include:
  - Handling missing values.
  - Renaming columns for clarity.
  - Formatting data (e.g., converting dates to a standard format).

### 3. Saving Cleaned Data
- The cleaned data is saved back to new Excel files for record-keeping and future use.

### 4. Database Interaction
- **Database**: The data is stored in a MySQL database named `Dataspark`.
- **Table Creation**: Tables are created if they do not already exist.
- **Data Insertion**: Cleaned data is inserted into the corresponding tables.

### 5. MySQL Connection Details
- The connection is established using the following details:
  - Host: `127.0.0.1`
  - User: `root`
  - Password: `Abdul@1973`
  - Database: `Dataspark`

## Requirements
- Python 3.x
- Pandas
- MySQL Connector for Python
- Jupyter Notebook

## How to Use
1. **Setup MySQL Database**: Ensure that your MySQL server is running and that the `Dataspark` database exists.
2. **Run the Notebook**: Open the Jupyter Notebook and execute the cells sequentially.
3. **Verify Data**: Check the MySQL database to ensure that the data has been correctly inserted.

## Output
- Cleaned data is saved as `Exchange_Rates_processed.xlsx` and `Customers_processed.xlsx`.
- Data is inserted into MySQL tables named `exchange_rates` and `customers1`.

## Authors
This process was documented and executed by [Mohamed Ashiq A].

## License
This project is licensed under the MIT License.
