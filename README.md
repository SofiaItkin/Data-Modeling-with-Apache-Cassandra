# Data-Modeling-with-Apache-Cassandra
The purpose of this project is to develop an ETL pipline using python for the construction of a data model in a non-relational database from cvs files. based on Apache Cassandra.

The process of creating a data model contains the following steps: 

1.Create unique primary keys - Each table in the model requires a unique primary key for query, updating and sorting data in the fastest and most efficient way. The primary key   will be constracted of Partion Keys or Clustering Columns.
2.Denormalization tables - The data must go through a denormalization process because non-relational databases can't use joins like relational database. 
3.Create tables in Apache Cassandra, Load Data into the tables and run queries for data quality check.


## Project Structure:

event_data - The directory of CSV files partitioned by date

Project_Notebook.ipynb- Notebook that Contain the project steps



## Installation:


Python and Jupyter Notebook must also be installed.

Cassandra instance needs to be up and running


