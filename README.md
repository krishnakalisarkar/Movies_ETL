# Movies_ETL

**Movie Analysis with ETL**

![Movie_image](https://png.pngtree.com/thumb_back/fw800/back_pic/00/09/00/35562c7854049dc.jpg)

## Overview of this project:

Extract Transform Load commonly know as ETL is a stepwise procedure of extracting, transforming and loading data to a database. It is an essential procedure because data is usually obtained from more than one source, in various-structured forms. Those huge stores of data need to be transformed into formats best suited for analysis. ETL prepares data for fast access and hence fast insight. 

## Purpose of this study: 

The main purpose of this ETL project is to prepare data for a hackathon. Hackathon is an event where teams of analysts collaborate to work intensively on a project, using data to solve a problem. For this hackathon, data is gathered from Wikipedia and Kaggle, combined and then saved into a SQL database for the  participants to work on. The process of ETL involves data extraction from Wikipedia and Kaggle, Transforming data by cleaning the data, making data look uniform under a column, making dataframes and finally joining various datasets. Joining the datasets is again following by some more data cleaning to remove repeating redundant data. The final step of the ETL process is loading the cleaned dataset into a SQL database.

## In this study:

In this study, data is obtained from Wikipedia, kaggle metadata and ratings data. This was followed by converting these datasets into DataFrames using pandas functions.
Once the dataframes were structured, each dataset was cleaned to remove duplicate values and null values. The Wikipedia dataset was joined with the kaggle metadata using inner joins and this was later joined with the ratings dataset using left joins.  
The combinded datasets were then loaded into the SQL database.
