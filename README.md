# Movies-ETL
Extract Transfer Load

![git-hub](https://github.com/MonaElahi/Movies-ETL/blob/3d433d939613911a309e8446b9ac0aac9fa6296e/Movies%20Image.jpeg)

# Overview 
In Amazing Prime Hackathon, automated pipeline is created that will take new data, from  Wikipedia data, Kaggle metadata and the MovieLens
rating data toperform the appropriate transformations, and loads the data into existing PostgreSQL Database.  

Following procedures have been performed.

- ETL Function to read three data files 

* movies_metadata.csv
* wikipedia-movies.json
* ratings.csv

- Extract and Transform the Wikipedia Data
- Extract and Transform the Kaggle data
- Create the Movie Database


# Resources 

- Data Source: wikipedia-movies.json, movies_metadata.csv, ratings.csv
- Software: Jupyter Notebook, PostgreSQL 11.9, pgAdmin 4


# Results 

### ETL Function to Read Three Data Files

Three separate "Pandas DataFrames" have been created by using the ETL process, by reading Data files. 


### Extract and Transform the Wikipedia Data

Cleaned and formatted wikipedia data by removing duplicates, null columns,
drop null values and convert data to string values.

### Extract and Transform the Kaggle data

Cleaned and formatted the Kaggle data then merged the Kaggle metadata DataFrame and MovieLens
rating data DataFrame with the Wikipedia movies DataFrame and 


### PostreSQL Movie Database

Finally, Added the movies DataFrame and MovieLens rating CSV data to a SQL Database  


# Summary

The ETL Function has been performed to collect and clean data files from different sources.  
Cleaned data then merged and transfered to PostgreSQL dataset tables to be used for analysis.
