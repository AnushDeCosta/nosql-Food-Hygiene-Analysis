# FoodQuest: A NoSQL Adventure in UK's Food Landscape

![Mongo](https://github.com/AnushDeCosta/nosql-Food-Hygiene-Analysis/assets/67308030/f800d6ff-fe5d-4151-bc2b-607c4c67b421)

## Introduction
This Analysis is organized into three distinct sections:
- Configuration of Database and Jupyter Notebook
- Database Modification
- Exploratory Examination

## Configuration of Database and Jupyter Notebook
In the project's opening section, data was drawn from a provided JSON file and deposited into a MongoDB database titled "uk_food", under a collection named "establishments". The PyMongo and Pretty Print libraries were used to ascertain the successful creation and data loading. The establishments collection was then assigned to a variable for subsequent utilization.

## Database Modification
In the second part of the project, alterations were made to the establishments collection in the uk_food database via the NoSQL_setup_starter.ipynb. I introduced a new eatery, "Penang Flavours", to the database with a rating in waiting, located and updated the BusinessTypeID for "Restaurant/Cafe/Canteen" for the newly added restaurant, eliminated all establishments within the Dover Local Authority from the database, and transitioned latitude and longitude values stored as strings into decimal numbers through update_many.

## Exploratory Examination
In the concluding section of the project, I utilized the NoSQL_analysis_starter.ipynb notebook to respond to specific inquiries by Eat Safe, Love, a food-focused magazine. These questions assisted the magazine editors in identifying desirable and undesirable locations. To answer these questions, I delved into the establishments collection:
- Which establishments had a hygiene score equal to 20?
- Which establishments in London had a RatingValue greater than or equal to 4?
- What were the top 5 establishments with a RatingValue of '5', sorted by lowest hygiene score, nearest to the newly added restaurant, "Penang Flavours"?
- How many establishments in each Local Authority area had a hygiene score of 0?
To extract the necessary data and convert it into Pandas DataFrames for easier analysis, I employed count_documents, pprint, and aggregation methods.

## Tools
- Jupyter Notebook
- VSCode
- MongoDB Compass
- Pandas
- Matplotlib
- Python
- Terminal

## Files
- Database and Jupyter Notebook Set Up and Update of the Database -
  - [Part 1 and Part 2](./NoSQL_setup_Final.ipynb)

- Exploratory Analysis -
  - [Part 3](./NoSQL_analysis_Final.ipynb)
