
# Data Processing and Database Ingestion

## Overview
This repository contains a Jupyter Notebook that demonstrates the process of loading, cleaning, and storing data into a MySQL database. The notebook is designed to process data from multiple Excel files, perform necessary cleaning operations, and insert the cleaned data into the database.

## Process Details

### 1. Loading Data
- The notebook loads data from five Excel files into pandas DataFrames.
- These files include data such as exchange rates, customer details, and potentially other related datasets.

### 2. Data Cleaning
- The cleaning process involves:
  - Handling missing values.
  - Renaming columns for clarity.
  - Formatting data, such as standardizing date formats.
  - Applying specific transformations required for each dataset.

### 3. Saving Cleaned Data
- The cleaned data from each of the five datasets is saved back to new Excel files for record-keeping and future use.

### 4. Database Interaction
- **Database**: The cleaned data is stored in a MySQL database named `Dataspark`.
- **Table Creation**: Tables are created if they do not already exist in the database.
- **Data Insertion**: Each of the cleaned datasets is inserted into corresponding tables within the MySQL database.

### 5. MySQL Connection Details
- The connection to the MySQL database is established using the following details:
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
2. **Run the Notebook**: Open the Jupyter Notebook and execute the cells sequentially to process the five datasets.
3. **Verify Data**: Check the MySQL database to ensure that all data has been correctly inserted.

## Output
- Cleaned data is saved as new Excel files for each of the five datasets.
- The data is inserted into the MySQL database in corresponding tables.

## Authors
This process was documented and executed by [Mohamed Ashiq A].

## License
This project is licensed under the MIT License.
