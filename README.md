# PyBer_Analysis

Deliverable 3: A written report for the PyBer analysis

Overview of Project

This exploratory analysis is out to provide insights to ride accessibility and affordability for Pyber a ride-sharing app-based company.
Our objective is to carryout exploratory data analysis on pyber share-ride data sets to determine the relationship between the city types, number of drivers and riders, including the percentage of total fare, rides and drivers by type of city.
To obtain this, we have to dive into creating several visualizations, write python scripts using panda’s library and matplotlib, to create various charts and graphs.
Hence, all this will enable better improvement to access ride sharing services at an affordable fare.

RESULTS
Using the Pandas groupby() function with the count() and sum() methods on PyBer DataFrame columns, we get the total number of rides, total number of drivers, and the total fares for each city type. We Then, calculated the average fare per ride and average fare per driver for each city type. Finally, add this data to a new DataFrame, and then formatted the columns to obtain the following summary result.
• The rural fares jumped to $200 and dropped till end of April.
• The urban fares started with an average of $1800 remained for a while before an increase to $2300.
• The suburban fares jumped in march to $1000 which was not profitable a fare and dropped in march and remained till mid-April

Ride-Sharing Summary DataFrame

SUMMARY
• The average fare per driver in rural cities comes the highest with $55.49 along with a mean ride count of 7, these amounts compared to $16 with an average round count of 24 in urban cities. Further questions need to be asked as to the reasons for this disparity.
• A better maintenance of driver count bracket across different city types could have an impact on fare per driver upper and lower count boundaries, which in turn help reduce mean fares.
• The rural city ratio of drivers to ride is 1 to 2. Research as to this reason will be a welcome development. Also, questions need to be answered on:
If rural cities are adequately covered on the map, with the actual market demand for Pyber ride-sharing app.
