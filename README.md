# Airlines Data Analysis with SQL and PySpark

## Overview

This project demonstrates how to perform data analysis on an airlines dataset using both SQL and PySpark. The dataset includes information about aircrafts, airports, flights, bookings, tickets, and other related data. The goal is to showcase skills in working with relational databases and big data frameworks.

## Dataset

The dataset used in this project is sourced from Kaggle and consists of the following tables:

1. **aircrafts_data**: Information about aircrafts including their model and range.
2. **airports_data**: Details about airports such as name, city, coordinates, and timezone.
3. **boarding_passes**: Information about boarding passes for flights.
4. **bookings**: Data about bookings including booking reference, date, and total amount.
5. **flights**: Details of flights including flight number, departure and arrival times, and status.
6. **seats**: Information about seats in aircrafts including fare conditions.
7. **ticket_flights**: Details about tickets and their associated flights.
8. **tickets**: Information about tickets including passenger details.

## Project Structure

- **SQLite Database Setup**: Script to create and load the dataset into a SQLite database.
- **Exploratory Data Analysis (EDA)**: Initial exploration of the data using pandas.
- **SQL Operations**: SQL queries to perform various data operations and analysis.
- **PySpark Setup and Operations**: Scripts to read the dataset into PySpark DataFrames and perform similar operations as the SQL queries.
- **Questions and Solutions**: A set of 15 questions (easy, medium, and difficult) and their solutions using both SQL and PySpark.
- **Documentation**: Detailed comments and explanations for each script.

## Getting Started

### Prerequisites

- Python 3.12
- SQLite
- pandas
- PySpark
- Jupyter Notebook

### Installation
   Install required Python packages:
   
     pip install pandas 
     pip install pyspark
   

3. Download the dataset from Kaggle and place the CSV files in the project directory.

### Usage

1. **SQLite Database Setup**:
    - Run the `EDA & SQL.ipynb` notebook to create and load the SQLite database with the dataset.

2. **Exploratory Data Analysis (EDA)**:
    - Explore the dataset schema and relationships using `EDA & SQL.ipynb`.

3. **SQL Operations**:
    - Execute SQL queries using the `EDA & SQL.ipynb` script to perform various data analysis tasks.

4. **PySpark Setup and Operations**:
    - Run the `PySpark.ipynb` notebook to perform data analysis using PySpark.

5. **Questions and Solutions**:
    - Review the `EDA & SQL.ipynb` and `PySpark.ipynb` for a set of 15 questions and their solutions using SQL and PySpark.


### Acknowledgments

- Kaggle for providing the dataset.
- The developers and maintainers of pandas, PySpark, and other open-source libraries used in this project.

