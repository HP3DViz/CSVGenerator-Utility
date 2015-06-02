# CSVGenerator-Utility
This utility will connect with SQL Server and generate data for Visualization

This utility will check in the db if the user has access to execute this utility or not. [User name is Windows NT used ID]
Uitlity will also check if user has access to Prod/ ITG/ DEV. It will connect accrodingly with the servers and execute the SQL query.
Query's are embedded in seperate txt files. 
We also have history in separate CSV file which we will merge with the final result set and then generate final CSV.
