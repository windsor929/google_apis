# google_apis
This repository is used to contain all of the edited versions of the Google Maps APIs (eg Google Distance Matrix, Geocoding, etc) tailored for my individual projects. Data is stored locally, so must pay attention to how to parse the inputted data for generalizability.

Currently there are two different APIs in use: the reverse geocoder and the distance matrix. The reverse geocoder takes in the latitude 
and longitudes and returns the state (if in the US) of the location. The distance matrix takes in the lat and long and returns the 
distnace of all possible comibinations of starting and ending.

# Dependancies
This repository uses the Google Maps Service Python (https://github.com/googlemaps/google-maps-services-python), so make sure to clone 
that into the repository before starting.

# Reverse Geolocation
Parameters:
-in_file: the csv file from which to read the latitude and longitude, under the headers of 'Latitude' and 'Longitude'
-api:     designates the script to use the reverse geocoder api, enter rev_geo
-api_key: enter your api key

# Distance Matrix
wrote this a while ago, so have to go back through and check
