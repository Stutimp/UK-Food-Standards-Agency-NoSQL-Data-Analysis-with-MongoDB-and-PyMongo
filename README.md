# NoSQL-challenge
Module- 12 Challenge on NOSQL
### Overview
The UK Food Standards Agency evaluates various establishments across the United Kingdom and gives them a food hygiene rating. As an assigned Data Analyst whom the editors of a food magazine have contracted, **Eat Safe, Love,**, I will evaluate some of the rating data to help their journalists and food critics decide where to focus future articles.

Here, I have divided my overall data research into three parts, they are:

1. Database and jupyter Notebook Set up:
- First, I imported the data provided, in the establishments.json file from my Terminal and named the database and the collection respectively as 'uk_food' and 'establishments'.
- Then, I imported the libraries, such as PyMongo, pandas, and Pretty Print, for the Jupyter Notebook setup and data analysis. 
-With the above process, I created an environment for working with the 'uk_food' MongoDB database and the 'establishments' collection within my Jupyter notebook, allowing me to perform data analysis or manipulation tasks as needed.

2. Update the database:
- I inserted new restaurant's ("Penang Flavours") information into the database by using the 'insert_one()' function and updated it with the BusinessTypeID number. 
- Using query tools, I found the total establishments in 'Dover' and deleted all of them together using the 'update_many()' and 'delete_many()' functions.
- I converted data type of 'RatingValue' into an integer, and the data type of 'Longitude' and 'latitude' into float numbers for further statistical calculations.

3. Exploratory Analysis:
The Editors of **Eat Safe, Love** have specific questions they want me to answer, which will help them find the locations they wish to visit and avoid. Hence, using Jupyter Notebook, I found the answers to the following questions using query tools, pretty print function, pipeline method, and aggregate methods:

(i) Which establishments have a hygiene score equal to 20?

(ii) Which establishments in London have a RatingValue greater than or equal to 4?

(iii) What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?

(iv) How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.

- I used the count_documents() function to list the correct number of documents in the filtered output.
Finally, I exported the resulting outputs into  Panda Dataframes and printed the results using the jupyter notebook. I also printed the total counts of rows in the final data frame.

Thank You!
