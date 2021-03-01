# Movies_ETL

Using two main data sources, the Wikipedia data and MovieLens data from Kaggle, cleaned the data using loops, functions, regular expressions. Merged the two datasets and added data to a SQL database
* Transformed Wikipedia data, using functions to consolidate overlapping columns, dropping duplicates and columns with more than 90% null values
* Converted lists into strings and used regular expressions to detect patterns of messy data and convert data to a standardized format suitable for analysis
* Converted columns to correct data types, merged the Wikipedia and Kaggle data using imdb link, removed unnecessary columns to create a clean, final merged dataset. 
* Created a database engine and connection string to upload finalized data to the database using the to_sql command
* Tools: Jupyter Notebook, Python (pandas, numpy, json, sqlalchemy), Postgres SQL
