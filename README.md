# Data-Science-Capstone-Neighbourhoods
Data Science Capstone (Coursera) Neighbourhoods Locations using Python  

## Exploring and clustering the neighborhoods in Toronto.

### Introduction:
I used Foursquare API to explore neighborhoods in selected Neighbourhoods in toronto.
The Foursquare explore function were used to get the most common venue categories in each neighborhood,
and then used this feature to group the neighborhoods into clusters. The k-means clustering algorithm were
used for the analysis. Finally, I used the Folium library to visualize the neighborhoods in Toronto and their emerging clusters.


#### Data Section:
The data used were scraped from wikipedia.The dataset consist of the boroughs, neighborhoods and the locations of them. The foursqaure api will be used to analyze
the places nearby these neighborhoods and see the proximity of important places from the corresponding neighborhoods.


#### Methodology Section

For analyzing the neighborhoods for toronto.
First we find the neighborhoods popular places using the explore section of thr foursquare api and then for each neighborhood we get the top 10 most common places and try to visualize then to get the similarities among them. Then, from the scikit learn library we use the k-means algorithms to cluster the places and see similarities for different neighborhoods and find similarities among them. The visulization is done through the folium library. To find similarities an unsupervised learning is used which helps in clustering places and is quite effective.
