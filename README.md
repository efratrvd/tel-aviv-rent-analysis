# tel-aviv-rent-analysis
An analysis of the rental market in Tel Aviv

## Description
In 2021 Tel Aviv was ruled as the most expensive city in the Worldwide Cost of Living report from the Economic Intelligence Unit. This property is reflected in the high housing costs for both rental and purchase in the city. In this project we would like to collect insights on Tel Aviv’s rental market by analyzing patterns in Tel Aviv house rental facebook groups. We intend to compare different parameters like the price, apartment size, location, proximity to main sites in the city etc.. to find interesting trends.


## Methods
Using Facebook’s graph api, we intend to collect posts from Tel Aviv house rental groups. Using text analysis tools, like regex expressions, we will collect from the posts interesting information like the location of the apartment (street), the price, size, house floor and number of rooms.
To analyze the data, we will create a graph where the nodes are the apartments from the posts and the edges are weighted by the distance between 2 apartments or the distance to central places in the city like Dizengoff center, train stations, party places, the beach, collected by using Google Maps API. We will run clustering algorithms on this graph and analyze the node data (apartment properties) in each cluster to find interesting insights.
