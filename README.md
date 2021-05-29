# Capstone Project: The Battle of German Cities

## Introduction

**Recommender systems:**  An essential role in our daily lives 
- E.g., Entrepreneurs seek the most suitable place to open a new business. 
- E.g., Tourists look for a better place to stay for their next travelling destination. 

**Business problem:** Find the best city to live in Germany
- Scenario:  Lisa, a freelance writer, is looking for a Germany city in Germany for living. 
- Requirement: A town having a good environment to optimize work-life balance and offering opportunities for leisure activities, she enjoys visiting museums and theatres in her free time.

## Data

**Data Acquisition**
- A list of the German cities 
- Latitude and longitude coordinates of these cities (in order to use latitude and longitude ) 

**Data Source**
- Simple Maps - Germany Cities Database (https://simplemaps.com/data/de-cities)
- Foursquare API (location technology platform) 


## Methodology

Step1. Data acquisition 
- Get the list of German cities and their latitude and longitude data from “Simple Maps” (in csv format )and convert it into a data frame.

Step2.  Data Pre-processing 
- Deleting rows having missing data (e.g., rows have no populating data), removing unnecessary columns and modify column names to make the data frame better for analysing.

Step3. Retrieve venue data
- Use Foursquare API to retrieve venue data.

Step4. Data exploration 
- Explore the data ncluding grouping the cities to discover how many venues in each city and the number of unique venues each city has. 

Step5. One-hot encoding:  
- Use one-hot encoding to understand the frequency of each venue category’s occurrence.=> Get top 10 most common venues for each city.

Step6. K-Means Clustering
- Find the optimal number of cluster and implement K-Means clustering
- Use Folium library to plot cities and clusters 
- Examine different clusters 


Please see slides and report(pdf file) for discussions and results. 


![image](https://user-images.githubusercontent.com/82377749/120071900-7fb08d80-c091-11eb-8580-be1a7e051c46.png)


- Simple Maps - Germany Cities Database (https://simplemaps.com/data/de-cities)
