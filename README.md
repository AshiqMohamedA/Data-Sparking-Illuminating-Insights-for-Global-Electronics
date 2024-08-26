# Data Processing, Database Ingestion, and Interactive Dashboard Creation

## Overview
This repository contains a Jupyter Notebook that demonstrates the process of loading, cleaning, storing data into a MySQL database, and creating an interactive Power BI dashboard. The notebook is designed to process data from multiple Excel files, perform necessary cleaning operations, and insert the cleaned data into the database, while the Power BI dashboard provides a visual representation of the insights derived from the data.

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

### 5. Creating an Interactive Power BI Dashboard
- **Data Import**: Import the cleaned data directly from the MySQL database into Power BI.
- **Visualization**: Create various visualizations to represent key metrics and insights such as customer demographics, sales trends, product performance, and exchange rate fluctuations.
- **Interactivity**: Build interactive elements like filters and slicers to enable dynamic exploration of the data by users.
- **Publishing**: Publish the dashboard to Power BI Service, allowing for sharing and collaboration within your organization.

### 6. MySQL Connection Details
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
- Power BI Desktop (for dashboard creation)

## How to Use
1. **Setup MySQL Database**: Ensure that your MySQL server is running and that the `Dataspark` database exists.
2. **Run the Notebook**: Open the Jupyter Notebook and execute the cells sequentially to process the five datasets.
3. **Create Power BI Dashboard**: Use Power BI Desktop to connect to the `Dataspark` database, and create an interactive dashboard.
4. **Verify Data**: Check the MySQL database to ensure that all data has been correctly inserted, and ensure the dashboard reflects accurate data.

## Output
- Cleaned data is saved as new Excel files for each of the five datasets.
- The data is inserted into the MySQL database in corresponding tables.
- An interactive Power BI dashboard is created for data exploration and visualization.

## Authors
This process was documented and executed by [Mohamed Ashiq A].

## License
This project is licensed under the MIT License.
