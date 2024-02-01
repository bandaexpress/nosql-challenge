# nosql-challenge
Module 12 Assignment from Columbia University Data Analytics Bootcamp

## Objective

Utilizing NoSQL, this repo creates a database to review restaurant data provided by the UK Food Standards Agency in 2022. 

### Part 1: Database and Jupyter Notebook Set Up
To begin, I've imported data from a json file using Terminal and saved it to a database. Using PyMongo and Pretty Print, I've created a Mongo Client to load the database. 
### Part 2: Update the Database
New restaurant information is added to the database and updated. 
### Part 3: Exploratory Analysis
The following questions are answered:

1. Which establishments have a hygiene score equal to 20?
2. Which establishments in London have a RatingValue greater than or equal to 4?
3. What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
4. How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.

## References
UK Food Standards Agency (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GB Contains public sector information licensed under the Open Government Licence v3.0. Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567, pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).
