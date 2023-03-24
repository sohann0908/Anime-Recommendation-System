# Anime Recommendation System

This repository contains the code for a recommendation system for anime. The system uses a combination of content-based filtering and collaborative filtering to recommend anime to users.


## Data Pre-processing
The first step in building the recommendation system is to pre-process the data. We read in three CSV files containing information about anime, including its title, rating, synopsis, and production studio. We checked for missing values and duplicates in the data and handled them accordingly. Finally, we merged the data into one dataframe for further analysis.

## EDA and Visualization
We explored the data visually by plotting various graphs and charts to understand the top-rated anime, the anime that users dropped the most, and the top anime based on the number of episodes. We also categorized the anime based on their rating and production studio.

## Recommendation
For recommendation, we used two techniques: content-based filtering and collaborative filtering. In content-based filtering, we used the KNN model to recommend anime based on the similarity of their types, studios, keywords, and top features. In collaborative filtering, we prepared the data to find the most similar anime and used a pivot table to get the correlation of one anime with others. Finally, we recommended anime based on the similarity score.

## Conclusion
This recommendation system is designed to help users discover new anime based on their preferences. The combination of content-based filtering and collaborative filtering provides accurate recommendations for users.

