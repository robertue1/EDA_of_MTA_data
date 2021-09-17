# WTWY - Analzying MTA and real state-data for optimization of the placement of canvassing street teams. 
Roberto Linares



# Abstract 

For this WTWY project, we wanted to reach the highest amount of people by using a limited amount street canvassing teams. With that goal in mind, we decided to analyze the traffic of individual entrances (to provide specific recommendations) within the MTA stations with the most traffic in the city. As one of the expectations by doing the gala is to get contributions, we decided to find the zip code with a higher increase in average rent price for the last six months, as an indication of the neighborhood desirability and income range, and analyze and recommend a station in the area.


# Design

We focused on determining which were the higher traffic MTA stations in the city in the months that lead to the time of the gala (February-June). After having found that information, we analyzed the results in base of the days, and finally, we did a granular study to determine specifically which entries were the most transited, having in mind being able to provide recommendations to the WTWY street teams that will include: which entry, what days and what times of the day to target.
Once we were able to provide initial results, we decided to broaden the study and include Zillow rental prices to find a high income and high occupancy neighborhood, analyze subway stations in the area and provide a recommendation that will target a population that could make significant contributions to the cause of WTWY.



# Data
The main data source for this project was the MTA turnstile data, which initially included more than 3.5 million rows, including cumulative entries and exits for each turnstile in the system in ~ 4-hour intervals. 4 months of data were ingested and analyzed.
The secondary data source was Zillow, which gave us access to the variation of rent prices in the city of New York categorized by zip codes. 7 months of recent data were analyzed.

# Algorithms

* Data Exploration: First observation of the data and its characteristics.
* Data Cleaning: Initially and almost throughout the entire process.
* Data Aggregation: Used to determine the highest traffic subway stations, by grouping turnstiles that belong to the same station.
* Data Visualization: To create an easier way to showcases the findings from the analysis.


# Tools

* SQLAlchemy for creating a bridge between a database and Python. 
* Numpy and Pandas for data manipulation
* Matplotlib and Seaborn for plotting

# Communication

Submitted PDF slides and 5 minutes presentation. 
