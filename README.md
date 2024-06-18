# nosql-challenge
# Module 12 Challenge

This challenge required use of NoSQL and Mongo skills learned in module 12, such as inserting new data and updating a database, querying for certain values within a collection, changing datatypes, converting results into Pandas dataframes, and aggregating queries.

__Part 1__ required using Git Bash (or Terminal) to import the establishments.json data that was provided. Once the data was imported, the database and collection were created. 

__Part 2__ instructed that a new restaurant was added to the collection and the collection was updated. Queries were created to return only certain fields/values and those results were used to update the new restaurant entry. Next, a certain subset of restaurants located in Dover were found and then removed from the collection. Finally, latitude and longtiude coordinates where changed to datatype 'double', RatingValue values were changed to 'integer' datatypes, and non-numerical RatingValue values were converted to None. The updated collection was saved and used in Part 3.

__Part 3__ was the exploratory analysis where queries included comparison operators such as $eq, $gte, $lte, etc.; a search required using latitude/longitude coordinates and finding other establishments within a certain proximity; and a final query that required creating an aggregation pipeline. All results have a section where the very first result is pretty printed, and the aggregated results were converted into corresponding Pandas dataframes.

### Resources
- Module 12 activities
- Xpert Learning Assistant
- https://www.mongodb.com/docs/manual/reference/operator/aggregation/type/
