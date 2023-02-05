## NBA_K_Means_Clustering
NBA players have become versatile over the years, in this analysis we are going to try to determine who has All-Stars potential based on their stats and analyze which cluster has a bigger impact on winning.

This project used data science and machine learning techniques to conduct clustering on NBA data, extracted from Basketball Reference with Selenium. Data cleaning, data visualization, feature selection, and scaling the data using Min Max were used to prepare the data for clustering. The number of clusters needed was determined, and each data point was labeled to create the clusters. The trained model was then used to analyze the clusters and explore insights. The results of the project can be used to gain a better understanding of the NBA and how teams and players are performing.

## Pipeline

1. Website we got the stats from https://www.basketball-reference.com/leagues/NBA_{}_per_game.html
2. Data Scraping - Use Selenium to extract the data out of the website above
3. Data warehousing - create some folders within my direftory to store the data ianad then saving them into a CSV
4. Data Manipulation - Cleaning the datasets by renaming columns & variables, checking for null values, etc...
5. Data visualization - Give us a good understanding of our data 
6. Feature selection - Selecting the features needed for our analysis
7. Scaling our data by using Min & Max
8. Elbow test - Help us determine how many clusters is necessary for our analysis.
9. PCA Analysis
10. Creating centroids and plot clusters.
