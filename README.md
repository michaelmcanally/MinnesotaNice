# MinnesotaNice

This repo is for the data analysis that tries to answer, which neighborhood (of the 102) in the Twin Cities of Minneapolis-St. Paul is the most quintessential 'Minnesota Nice'?

Data was collected from multiple sources, including the Google geocoding API, Foursquare API, Walkscore API, the 2010 Census, and the 2013 American Community Survey.

The analysis creates a 'Minnesota Nice' score that is dependent on a variety of metrics pulled from the Census and American Community Survey, and synthesized from Foursquare data. This then is used to report out a 'top ten' list for Twin City neighborhoods.

To further scrutinize the neighborhoods, I perform a K-means clustering to analyze the different neighborhoods for similarity. The work suggests cluster sizes of 4, 6, or 8 would be appropriate. I chose a size of 6 and report out top ten lists for each of the clusters. Furthermore, the cluster analysis when plotted on maps suggests that the flavor of a neighborhood is highly dependent on it's neighborhood 'neighbor'. This was slightly unexpected, as the clustering analysis explicitly lacked any geographic information for cluster assignments.



