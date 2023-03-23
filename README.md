## Instructions

### Part 1: Analyze and Explore the Climate Data
In this section, you’ll use Python and SQLAlchemy to do a basic climate analysis and data exploration of your climate database. Specifically, you’ll use SQLAlchemy ORM queries, Pandas, and Matplotlib.

#### Precipitation Analysis
1. Find the most recent date in the dataset.\
![image](https://user-images.githubusercontent.com/62813833/227226533-19a3ebb0-67a1-4f35-b0a6-6c0de041c831.png)
2. Using that date, get the previous 12 months of precipitation data by querying the previous 12 months of data.
3. Select only the "date" and "prcp" values.
4. Load the query results into a Pandas DataFrame, and set the index to the "date" column.
5. Sort the DataFrame values by "date".
6. Plot the results by using the DataFrame plot method.
![image](https://user-images.githubusercontent.com/62813833/227226256-275a86ee-d2ce-4e38-91f2-e9817828b278.png)
7. Use Pandas to print the summary statistics for the precipitation data.
![image](https://user-images.githubusercontent.com/62813833/227226360-497f4b9c-eb8b-41e8-ac6d-9529e68aae98.png)

#### Station Analysis
1. Design a query to calculate the total number of stations in the dataset.
![image](https://user-images.githubusercontent.com/62813833/227226730-f9252b14-e61a-4d76-9f6d-a98e6719f0bc.png)
2. Design a query to find the most-active stations (that is, the stations that have the most rows). 
![image](https://user-images.githubusercontent.com/62813833/227227018-f7040cbb-f2ff-4cef-8164-f9bb0fce302e.png)
3. Design a query that calculates the lowest, highest, and average temperatures that filters on the most-active station id found in the previous query.
![image](https://user-images.githubusercontent.com/62813833/227227189-143f1702-e377-49b8-9019-c8de60d8121b.png)
4. Design a query to get the previous 12 months of temperature observation (TOBS) data. 
![image](https://user-images.githubusercontent.com/62813833/227227373-01f64b86-8fa8-4548-bfe3-3bd35bedd8a5.png)

### Part 2: Design Your Climate App
Now that you’ve completed your initial analysis, you’ll design a Flask API based on the queries that you just developed. 
