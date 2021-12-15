## Abstract

The goal of this project Exploratory Data Analysis to around the top 5 busiest station in New York in order to help our Company to open a booth in a metro station located in New York to sell its products, aiming to increase its profits during **the summer season from June 2019 to September 2019.** 

## Design
This project originated from our Company needs to increase their sales. The data is provided by NYC MTA traffic data. Our team uses NYC MTA data to locate the top 5 busiest stations in NYC in order to have an of each station's high number of entries. After that, our team used the results of our analysis to determine which station would be most suitable for our Company.

## Data
The NYC MTA dataset contains a few feature highlights include Date, Time (4-hour increments for each day which represent a single traffic reading per turnstile), Station name, Entries and Exits.

###	Scope

•	**Sample Size:** reading the data for the date from June 2019 to September 2019.

•	**Rows:** 3,714,064 rows.

•	**Columns:** 11 columns, which are C/A, UNIT, SCP, STATION, LINENAME, DIVISION, DATE, TIME, DESC, ENTRIES AND EXITS.
 
 ## Algorithms

•	Stripping columns from whitespace.

•	Combining the DATE and TIME columns into one column.

•	Calculating the difference between ENTRIES per a unique turnstile to get DAILY ENTRIES. 

•	Calculating the difference between EXITS per a unique turnstile to get DAILY EXITS.

•	Removing Duplicate and outliers.

## Tools
These are the technologies and libraries that I used for this project:
Technologies: SQLAlchomy, Python, Jupyter Notebook.
Libraries: Pandas, Numby, Matplotlib, Seaborn.
 
 ## Communication
 
 Top 5 Stations are more crowded
 
<img width="695" alt="Screen Shot 2021-10-10 at 1 33 56 PM" src="https://user-images.githubusercontent.com/90618007/146269695-4aa4ab8e-c46f-46db-b8e2-9f9135c10acc.png">

 
 these is busiest stations at NY in Midtown Manhattan 
 
<img width="800" alt="Screen Shot 2021-10-09 at 1 57 34 PM" src="https://user-images.githubusercontent.com/90618007/146269716-39a48f37-58df-4a78-bdbf-5c850f988a33.png">

<img width="788" alt="Screen Shot 2021-10-09 at 1 58 22 PM" src="https://user-images.githubusercontent.com/90618007/146269730-a48eded9-58c0-460e-813b-e30254573d9b.png">



