# nosql-challenge
in this module, i worked on an exploratory analysis of restaurant data using mongodb and python. the analysis included querying the database, performing data transformations, and generating insights from the data. here are the key tasks i completed:

part 1: data retrieval and initial exploration

i connected to the mongodb database using the official python driver, pymongo.
i reviewed the collections within the database to get an initial understanding of the data structure and content.

part 2: database update and data transformation
i inserted a new restaurant, "penang flavours," into the database.
i found and updated the businesstypeid for "restaurant/cafe/canteen" for "penang flavours."
i identified and deleted all documents with "dover local authority."
i converted latitude, longitude, and ratingvalue from strings to numbers.

part 3: exploratory analysis
i queried the database to find establishments with a hygiene score of 20.
i identified establishments in london with a ratingvalue greater than or equal to 4.
i found the top 5 establishments with a ratingvalue of 5, sorted by hygiene score and proximity to "penang flavours."
i determined the number of establishments in each local authority area with a hygiene score of 0.

resources:
ASKBCS: i use them to query the code as i recived an error in the installation and actual code
https://pymongo.readthedocs.io/en/stable/tutorial.html helped with getting started
https://www.mongodb.com/docs/manual/tutorial/query-documents/ help with query

