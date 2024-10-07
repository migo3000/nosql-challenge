NoSQL Challenge - UK Food Establishments Analysis

Overview

This project is part of the Module 12 Challenge, where the UK Food Standards Agency's establishments data is analyzed to provide insights for a food magazine named Eat Safe, Love. We used MongoDB to store and manipulate the data, leveraging Python's pymongo library for database interactions, and pandas for data analysis.

The analysis involved exploring food establishment data, updating the database, and answering specific questions for the magazine editors.

Files in Repository

NoSQL_setup_starter.ipynb: This notebook is used for setting up the MongoDB database, updating records, and ensuring data is properly prepared.

NoSQL_analysis_starter.ipynb: This notebook contains all the exploratory analyses requested by the editors, such as identifying establishments by hygiene scores, location, and other criteria.

establishments.json: This JSON file contains the raw data provided by the UK Food Standards Agency.

Steps Completed

Part 1: Database and Notebook Setup

Imported data from establishments.json to MongoDB using mongoimport.

Verified the database and collection were properly set up.

Part 2: Database Updates

Added a new restaurant named "Penang Flavours" to the database.

Updated the BusinessTypeID for "Restaurant/Cafe/Canteen".

Removed all establishments from the Dover local authority.

Converted fields like latitude, longitude, and RatingValue from strings to numeric types.

Part 3: Exploratory Analysis

Establishments with a Hygiene Score of 20: Found and analyzed establishments with the highest hygiene issues.

Establishments in London with a RatingValue of 4 or Higher: Filtered establishments based on rating criteria.

Top 5 Establishments near "Penang Flavours": Identified top-rated establishments closest to "Penang Flavours".

Establishments by Local Authority with a Hygiene Score of 0: Aggregated establishments with a hygiene score of 0, sorted by local authority.

Data Source

The data used in this project was provided as part of the Module 12 Challenge and was sourced from the UK Food Standards Agency.

Code Sources

Some parts of the code were inspired by examples covered in the course material and discussions with peers. Additionally, online forums like Stack Overflow were consulted for troubleshooting and best practices. Specific references are noted in the code comments where applicable.

How to Run

Clone the repository to your local machine.

Set up MongoDB and make sure it's running on localhost:27017.

Run the NoSQL_setup_starter.ipynb to import data and update the database.

Run the NoSQL_analysis_starter.ipynb to perform the exploratory analysis.

License

This project is for educational purposes only as part of the Module 12 Challenge in the course curriculum.

Acknowledgments

Instructors and TAs for guidance.

Peers for collaboration and support.

Stack Overflow for solutions to common issues.
