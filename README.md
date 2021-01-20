# Spotify_Top_200_Analysis
Analysis of the top 200 tracks on Spotify by their audio features made available through Spotify's API service. Partnered with Jake Bell.

This project was completed by Jake Bell and Sean Lovullo as required by the Mathematical Modeling course at Point Loma Nazarene University.

Spotify is one of the largest media streaming services, with over 50 million songs available and over 250 million monthly users. How does Spotify offer song suggestions to its users? It generates data on every song over multiple categories and uses them to find songs to suggest based on what you like. Publicly accessible features include song length, key, mode, time signature, acousticness, danceability, energy, instrumentalness, liveness, loudness, speechiness, valence, and tempo. Pooling data that is publicly available, we want to answer the following question: can we predict the number of streams a Top 200 song on Spotify will get by finding clusters within the data that are based on the given audio features?  

To find an answer, we will utilize the K-Means clustering algorithm to cluster the top 200 tracks into groups based on Spotify's audio features. Then we will construct a number multiple regression models; there will be one for each cluster and also one ignoring the clusters. We will train the models using 80% of our data and test the models with the remaining 20% to see how well the model fits new data.  
 
To accomplish these tasks, we will use both R and Python. R will be utilized to generate the data set in real-time, to do much of the data wrangling, and to visualize and model the data. Python (particularly the sci-kit learn package) is used to run the K-Means algorithm to cluster the data, as well as preparing the data to be used in that algorithm.  
