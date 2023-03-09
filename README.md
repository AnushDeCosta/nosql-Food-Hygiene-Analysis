# nosql-challenge

# BootCamp - Module 12 Challenge

Student Name - Anush De Costa Module 12 Challenge Name - NOSQL-Challenge

## Introduction

This project consists of three main parts:

- Database and Jupyter Notebook Set Up
- Update the Database
- Exploratory Analysis

## Database and Jupyter Notebook Set Up

In the first section of the challenge, I imported data from a provided JSON file into a MongoDB database named "uk_food" and a collection named "establishments". I used PyMongo and Pretty Print libraries to confirm the successful creation and loading of the data, and assigned the establishments collection to a variable to prepare for further use.

## Update the Database

In section two of the challenge, I made modifications to the establishments collection in the uk_food database using NoSQL_setup_starter.ipynb. I added a new restaurant, Penang Flavours, to the database with a pending rating, found and updated the BusinessTypeID for "Restaurant/Cafe/Canteen" for the new restaurant, removed all establishments within the Dover Local Authority from the database, and converted the latitude and longitude values stored as strings to decimal numbers using update_many.

## Exploratory Analysis

In the final section of the challenge, I used the NoSQL_analysis_starter.ipynb notebook to answer specific questions requested by Eat Safe, Love, a food magazine. The questions helped the magazine editors find the locations they wished to visit and avoid. I explored the establishments collection to find the answers to the following questions:

- Which establishments had a hygiene score equal to 20?
- Which establishments in London had a RatingValue greater than or equal to 4?
- What were the top 5 establishments with a RatingValue of '5', sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
- How many establishments in each Local Authority area had a hygiene score of 0?

I used count_documents, pprint, and aggregation methods to retrieve the necessary data and convert it to Pandas DataFrames for easier analysis.

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
