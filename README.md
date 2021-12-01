# Scrape and Visuzalize Lime Mobility Data from Washington DC

Companies are required to provide anonymized trip data to District Department of Transportation of Washington DC.

DDOT states that their goal "is to protect the privacy of dockless bikeshare users while maintaining transparency for the residents of the District".

This notebook explains how to scrape Lime Mobility data from Dockless Data and Application Programming Interface (API) using Python.

Visualization covers instantenaous locations and types of mobility vehicles and does not contain historical data.

Data includes:

bike_id	        unique bike id
lat	            latitude
lon	            longitude
is_reserved	    reservation status
is_disabled	    disable status
vehicle_type	  vehicle type (bike, moped, etc...)

Data is scraped as json and converted to pandas dataframe. For visualization purposes Plotly is used. 
