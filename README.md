# nosql-challenge
## Overview
This project involves analyzing UK food hygiene rating data obtained from the UK Food Standards Agency API.

## Directory Structure
1. **Resources Folder**: Contains establishments.json file.
2. **NoSQL_analysis_starter.ipynb**: Jupyter Notebook file for NoSQL data analysis.
3. **NoSQL_setup_starter.ipynb**: Jupyter Notebook file for NoSQL database setup.
4. **README.md**: Project documentation file.

## Dependencies
- `pymongo`: Python library for interacting with MongoDB.
- `pprint`: Python library for pretty printing.
- `pandas`: Python library for data manipulation and analysis.

## Project Tasks
1. Set up NoSQL database.
2. Question 1: Which establishments have a hygiene score equal to 20? 
3. Question 2: Which establishments in London have a RatingValue greater than or equal to 4?
4. Question 3: What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
5. How many establishments in each Local Authority area have a hygiene score of 0?


## Instructions
1. Ensure you have the required libraries installed by running the following command in your terminal:

   pip install pymongo pprint pandas


2. Run NoSQL_setup_starter.ipynb to set up the MongoDB database.
3. Execute NoSQL_analysis_starter.ipynb for data analysis and visualization.

## References
- UK Food Standards Agency API: [UK food hygiene rating data API](https://ratings.food.gov.uk/open-data/en-GB)
- Data Licensing: Contains public sector information licensed under the Open Government Licence v3.0

