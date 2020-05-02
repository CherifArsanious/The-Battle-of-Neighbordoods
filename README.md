# The-Battle-of-Neighbordoods
# Coursera_Capstone_The_Battle_of_Neighborhoods
## Introduction to Problem
I want to help entrepreneurs in exploring better locations for their startups projects(restaurants, cafe, pharmacies) around the district of Cairo Egypt. It will help them make smart and efficient decisions on deciding which location to open their startup neighborhoods in Cairo district, Egypt. It has always been difficult in Egypt to find that kind of information. Usually entrepreneurs have to rely on very scarce data and just depend on their observations and hunches to select a location for their startups cafe or restaurants.
 
## The Location
Cairo is a popular destination for new immigrants in Egypt to explore or start new projects.It is the capital of Egypt. Cairo Governorateis the most populated of the governorates of Egypt. Its capital, the city of Cairo, is the national capital of Egypt, and is part of the Greater Cairo metropolitan area.

## Data used

### Foursquare API
This project would use Four-square API as its prime data gathering source as it has a database of millions of places, especially their places API which provides the ability to perform location search, location sharing and details about a business. 

### Wikipedia and web scraping
Web scraping to get the different neighborhoods of Cairo district and also webscraping and manual search to get the latitudes and longitudes of all Cairo neighborhoos as sometimes these kind of information is not readily available as ready tables.

## Work Flow
Using credentials of Foursquare API features of near-by places of the neighborhoods would be mined. Due to http request limitations the number of places per neighborhood parameter would reasonably be set to 100 and the radius parameter would be set to 500.

## Libraries Which are Used to Develope the Project
Pandas: For creating and manipulating dataframes.
Folium: Python visualization library would be used to visualize the neighborhoods cluster distribution of using interactive leaflet map.
Scikit Learn: For importing k-means clustering.
JSON: Library to handle JSON files.
XML: To separate data from presentation and XML stores data in plain text format.
Geocoder: To retrieve Location Data.
Beautiful Soup and Requests: To scrap and library to handle http requests.
Matplotlib: Python Plotting Module.
