# Relational Databases and pandas

## Relational Database Structure
A database is an organized collection of data that is structured to facilitate the storage, retrieval, modification, and deletion of data.
There are two main types of databases: relational databases and non-relational databases, with relational being the most popular. 
SQL, or Structured Query Language, is the standard language for communicating with relational databases.

## Relational Databases in Python
That is necessary when we have large amounts of data, which is where SQL and other databases excel over flat files.

- So in this notebook I Connect to a database, connect to a SQLite database using SQLAlchemy, a database toolkit for Python.

  - Check out the docs: https://www.sqlalchemy.org/

- Then Store the data in the cleaned master dataset in that database using pandas' to_csv DataFrame method.
- Then read the brand new data in that database back into a pandas DataFrame using pandas' read_csv function.
