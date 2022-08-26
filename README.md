# Movies-ETL

## Project Overview
Perfroming an ETL process by adding data to PostgreSQL database to create a automated pipeline that will take new data from Wikipedia data, Kaggle metadata, and MovieLens rating data. Using the data to perfrom transformations and will load it into existing tables. 
The following steps we used:
  
  1. write an ETL function to read three data files,
  2. extract and transform the Wikipedia data,
  3. extract and transform the Kaggle and rating data,
  4. load the data to a PostgreSQL Movie Database.

## Results
### Write an ETL function to read three data files
The function takes the Wikipedia JSON, the Kaggle metadata and MovieLens csv files and creates three separate DataFrames.

### Extract and Transform the Wikipedia data
We filtered out the TV shows, consolidated the redundant data, removed the duplicates and formatted the Wikipedia data.

### Extract and Transform the Kaggle and rating data
Again, we consolidated the redundant data, removed the duplicates, formatted and grouped the data.
The Kaggle and rating data were then merged with the Wikipedia movies DataFrame.

### Load the data to a PostgreSQL Movie Database

## Summary
