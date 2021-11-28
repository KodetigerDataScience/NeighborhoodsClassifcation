# Neighbourhood_Classification
Classification of London neighbourhoods based on nearby venues to each neighbourhood

#### Business Problem

A new and popular coffee-chain from Newyork wants to set up a few branches in London.
It wants to explore all the neighbourhoods in London based on the types of venues in each neighbourhood
and target those locations which are not already overcrowded with caffes and coffee shops , but still have decent amount of venues 
in the neighbourhood, plus has good connectivity with train and bus(based on train stations and bus stops in the neighbourhood).

So the full project involves finding the list of neighbourhoods of London, finding the location coordinates for each, finding upto 50 
venues in each neighborhood in a radius of 500 metres and classifying/clustering the neighbourhoods based on most frequently
occuring venues in each neighbourhood.  

####Solution

####Project Steps:

-Get the list of Neighborhoods from web(wikipedia) .

-Find the location coordinates for each Neighbourhood using geopy library.

-Find upto 50 nearby venues in each neighboruhood within a radius of 500 m using the Foursquare API.

-Cluster the neighbourhoods based on the type of most common venues in the neighbourhood using KMeans Clustering Algorithm

-Plot the neighbourhoods based on Labels using Folium library.

#### Libraries Used

- Pandas, Numpy, Matplotlib, Sklearn, Folium
