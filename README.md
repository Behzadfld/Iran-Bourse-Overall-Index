1. Database Description
   This project focuses on analyzing the Iran Stock Market Overall Index from 2008 to 2023 using SQL Server.
   The main goal is to study market trends, daily and monthly changes, volatility, and breakout points based on historical index data.
   The database consists of one main table that stores daily index values and related trading information, which is used for analytical SQL queries.

2. ERD (Entity-Relationship Diagram)
   The database follows a simple structure with a single entity:
   Overall_Index
   • DTYYYYMMDD (Date)
   • OPEN
   • HIGH
   • LOW
   • CLOSE
   • VOL
   • OPENINT (x3)
   Since the project is analytical, no complex relationships between multiple tables are required.
   All analyses are performed on the main table using SQL queries and window functions.

3. Installation and Setup Guide
   Required Software
   • Microsoft SQL Server
   • SQL Server Management Studio (SSMS)
   • Microsoft Excel (for viewing and converting dataset files)
   Setup Steps
4. Download the dataset from Kaggle:
   https://www.kaggle.com/datasets/nimapourmoradi/iran-bourse-overal-index/data  
   The dataset file is also included in the `docs` folder of this repository.
5. Convert the Excel file to CSV format.
6. Create a new database in SQL Server.
7. Import the CSV file using Import Flat File in SSMS.
8. Execute the provided SQL scripts to create tables and run analytical queries.
   All SQL queries can be executed directly in SSMS without additional configuration.
