# "Eat Safe, Love" Food Magazine Ratings Analysis

### Repository Overview 
- The script to aggregate each part of the analysis can be found in the "Starter_Code" folder
- The JSON file for you to upload can be found in the "Resources" folder within the "Starter_Code" folder

### Background 
The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

# Steps to take Prior to Running the Code
- In your Terminal, import the 'establishments.json' file using "mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json"
- Once you open up your Jupyter Notebook file, make sure you import 'PyMongo' and 'Pretty Print'
- Create an instance of Mongo Client


# Ratings Analysis Summary 

- 41 establishments have a hygiene score of 20
- 33 establishments in Longon have a Rating Value greater than or equal to 4
- 7,209 establishments total between each Local Authority area have a hygiene score of 0. Thanet has the largest number with 1,130 establishments and Tendring has the lowest number with 542 establishments that have a hygiene score of 0 

