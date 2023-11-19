# nosql-challenge

# Work Summary for Eat Safe, Love Project

## Part 1: Database and Jupyter Notebook Set Up
In this section, the task was to set up the MongoDB database named "uk_food" and the collection "establishments." The data from the "establishments.json" file was imported into the database. The Jupyter Notebook "NoSQL_setup_starter.ipynb" was utilized for this purpose.

## Steps:
Imported data from "establishments.json" into the "uk_food" database and "establishments" collection.
Verified the proper setup by listing databases and collections in MongoDB.
Confirmed the existence of "uk_food" database and "establishments" collection.
Displayed one document from the "establishments" collection using the find_one method.
Assigned the "establishments" collection to a variable for further use.

## Part 2: Update the Database
The focus of this part was to make specific modifications to the "establishments" collection based on requests from the magazine editors.

## Changes Made:
Added information for a new halal restaurant, "Penang Flavours," in Greenwich, with a pending rating.
Found and returned the BusinessTypeID for "Restaurant/Cafe/Canteen" and updated the new restaurant with this BusinessTypeID.
Removed establishments in Dover Local Authority from the database as per the magazine's request.
Converted certain number values stored as strings to actual numbers using update_many.

## Part 3: Exploratory Analysis
This section involved exploring the dataset and finding answers to specific questions posed by Eat Safe, Love to assist their decision-making for future articles.

## Questions Explored:
Identified establishments with a hygiene score equal to 20.
Found establishments in London with a RatingValue greater than or equal to 4.
Determined the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to "Penang Flavours."
Calculated the number of establishments in each Local Authority area with a hygiene score of 0, sorted from highest to lowest.

Note: This summary is a concise overview of the work done. For detailed steps and code, refer to the respective Jupyter Notebooks.


# Resources: 

During this assignment the great help came from tutor Kourt Bailey and assistence of AskBCS Learning Assistant.
Also some references from stackoverflow used:

https://stackoverflow.com/questions/62543377/mongodb-update-data-type-of-field/62544816#62544816


