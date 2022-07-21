# predicting-taxi-ride-duration
The goal of this project is to create a regression model that predicts the travel time of the taxi ride in New York.
The 'taxi.csv' file contains the dataset of the New York taxi rides for 2016 year. 
The 'main.ipynb' file contains the jupyter notebooks cells with the code. This file consists of dataset exploration, data selection, EDA, feauture engineering, and model selection

The Data: 
Columns of the manhattan_taxi table include:

pickup_datetime: date and time when the meter was engaged
dropoff_datetime: date and time when the meter was disengaged
pickup_lon: the longitude where the meter was engaged
pickup_lat: the latitude where the meter was engaged
dropoff_lon: the longitude where the meter was disengaged
dropoff_lat: the latitude where the meter was disengaged
passengers: the number of passengers in the vehicle (driver entered value)
distance: trip distance
duration: duration of the trip in seconds

The main goal is to predict duration from the pick-up time, pick-up and drop-off locations, and distance.

