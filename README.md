# sqlalchemy-challenge

Climate Analysis and Flask App README

Part 1: Analyzing and Exploring Climate Data

Setup:

Connect to the SQLite database using SQLAlchemy's create_engine() function.
Use automap_base() to reflect database tables into classes: Station and Measurement.
Create a session to link Python to the database.
Precipitation Analysis:

Identify the most recent date in the dataset.
Retrieve the previous 12 months of precipitation data.
Load the data into a Pandas DataFrame and set column names.
Sort the DataFrame by date and plot the results using Matplotlib.
Print summary statistics for the precipitation data.
Station Analysis:

Calculate the total number of stations in the dataset.
Determine the most active stations by listing stations and their observation counts in descending order.
Identify the station with the highest number of observations.
Calculate the lowest, highest, and average temperatures for the most active station.
Query the previous 12 months of temperature observation (TOBS) data for the most active station and plot it as a histogram.
Closing:

Close the SQLAlchemy session.