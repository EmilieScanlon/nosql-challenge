# nosql-challenge
Objective:

The objective of this assignment is to set up a NoSQL database, modify it according to the magazine editors' requests, and perform exploratory analysis to answer specific questions about the data.

Database Setup:

Add a new halal restaurant to the database
Remove establishments in Dover Local Authority
Convert latitude, longitude, and RatingValue fields to numeric values
Exploratory Analysis:

Find establishments with a hygiene score equal to 20
Find establishments in London with a RatingValue greater than or equal to 4
Find the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant "Penang Flavours"
Find the number of establishments in each Local Authority area with a hygiene score of 0, sorted from highest to lowest
Files:

NoSQL_setup_starter.ipynb: Notebook for setting up the database
NoSQL_analysis_starter.ipynb: Notebook for performing exploratory analysis
Note:

The dataset contains information about establishments, including their ratings, scores, and locations.
The RatingValue field ranges from 1-5, with higher values indicating better ratings.
The scores for Hygiene, Structural, and ConfidenceInManagement work in reverse, with higher values indicating worse performance.
