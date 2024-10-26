# star-api

This project consists of python files to parse the project CSV to gain insight data.

## Pre-requisites

- Python 3.10 or higher
- Python Libraries
  - pandas
  - sqlalchemy
  - jupyter
  - matplotlib
  - seaborn

## 01_csv_data_scrub

The customer information and transaction `csv` has to be present in the project folder to run this script. The original data is scrubbed on few assumptions and is then converted to a `database (db)` file.

## 02_customer_info

Insights on the customer information is provided by parsing the `db` file with SQL. The results are stored in `pandas` dataframe and is then plotted to visualize the findings.

## 03_customer_transaction

Insights on customer transactions are provided.

## sqldb.py

This python file consists of a custom class that has methods to parse the query and also to plot the data.

## CaseStudy.ppt

Provides detail analysis and insight on the project metrics