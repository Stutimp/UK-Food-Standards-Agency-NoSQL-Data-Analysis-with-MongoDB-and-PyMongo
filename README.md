# UK-Food-Standards-Agency-NoSQL-Data-Analysis-with-MongoDB-and-PyMongo

# Project Overview

This project aims to analyze the UK Food Standards Agency's food hygiene ratings data. The UK Food Standards Agency evaluates various establishments across the United Kingdom and gives them a food hygiene rating. As an assigned Data Analyst whom the editors of a food magazine have contracted, **Eat Safe, Love,**, I will evaluate some of the rating data to help their journalists and food critics decide where to focus future articles.

The challenge is divided into three parts: database setup, database update, and exploratory analysis.

## Part 1

1. **Database and Jupyter Notebook Setup**

- First, I imported the data provided, in the establishments.json file from my Terminal and named the database and the collection respectively as 'uk_food' and 'establishments'.
- Then, I imported the libraries, such as PyMongo, pandas, and Pretty Print, for the Jupyter Notebook setup and data analysis. 
-With the above process, I created an environment for working with the 'uk_food' MongoDB database and the 'establishments' collection within my Jupyter notebook, allowing me to perform data analysis or manipulation tasks as needed.

## Part 2

2. **Update the database:**

- I inserted new restaurant's ("Penang Flavours") information into the database by using the 'insert_one()' function and updated it with the BusinessTypeID number. 
- Using query tools, I found the total establishments in 'Dover' and deleted all of them together using the 'update_many()' and 'delete_many()' functions.
- I converted data type of 'RatingValue' into an integer, and the data type of 'Longitude' and 'latitude' into float numbers for further statistical calculations.

## Part 3

3. **Exploratory Analysis:**
The Editors of **Eat Safe, Love** have specific questions they want me to answer, which will help them find the locations they wish to visit and avoid. Hence, using Jupyter Notebook, I found the answers to the following questions using query tools, pretty print function, pipeline method, and aggregate methods:

(i) Which establishments have a hygiene score equal to 20?

(ii) Which establishments in London have a RatingValue greater than or equal to 4?

(iii) What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?

(iv) How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.

- I used the count_documents() function to list the correct number of documents in the filtered output.
Finally, I exported the resulting outputs into  Panda Dataframes and printed the results using the jupyter notebook. I also printed the total counts of rows in the final data frame.

## Conclusions
This project highlighted the effectiveness of MongoDB, PyMongo, and Jupyter Notebooks in managing and analyzing diverse data structures. Key conclusions include:

- **Efficient Data Management:** MongoDB's document-oriented model allows for flexible and efficient data storage and retrieval.
- **Dynamic Schema Flexibility:** The ability to modify data without a rigid schema facilitates handling unstructured data.
- **Powerful Query Capabilities:** PyMongo enables complex data retrieval and aggregation queries.
- **Scalability and Performance:** MongoDB efficiently handles large volumes of data, demonstrating high performance and scalability.
- **Visualization and Analysis:** Jupyter Notebooks provide an interactive environment for documenting, visualizing, and presenting data analysis.

## Applications
The tools and techniques used have wide-ranging applications:

- **Food Safety and Public Health:** Monitoring and analyzing food hygiene ratings to improve standards.
- **Restaurant and Hospitality:** Benchmarking performance and ensuring compliance with health regulations.
- **Big Data Analytics:** Managing and analyzing large datasets across various industries.
- **Real-Time Data Processing:** Suitable for applications like IoT sensor data monitoring.
- **Business Intelligence:** Enabling data-driven decision-making and strategy optimization.
- **Research and Academia:** Providing practical experience in NoSQL databases and data analysis.

These methods empower organizations to manage complex datasets, perform sophisticated analyses, and drive informed decision-making.

Thank You!

Author

Stuti Poudel
