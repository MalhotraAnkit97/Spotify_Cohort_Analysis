Spotify Song Cohort Analysis
Project Description
The customer always looks forward to specialized treatment, whether shopping over an e-commerce website or watching Netflix. They want what they might like to see. To keep the customers engaged, it is also crucial for companies to always present the most relevant information. Spotify is a Swedish audio streaming and media service provider. The company has over 456 million active monthly users, including over 195 million paying subscribers, as of September 2022. The company intends to create cohorts of different songs that will aid in the recommendation of songs to users based on various relevant features. Each cohort would contain similar types of songs.
Problem Objective
As a data scientist, the goal is to perform exploratory data analysis and cluster analysis to create cohorts of songs. The aim is to gain a better understanding of the various factors that contribute to creating a cohort of songs.
Data Description
The dataset contains data from Spotify's API about all albums for the Rolling Stones listed on Spotify. It is important to note that all songs have unique IDs.
Key Features
song_id: Unique identifier for each song
song_name: Name of the song
artist_name: Name of the artist
album_name: Name of the album
duration_ms: Duration of the song in milliseconds
explicit: Indicates whether the song contains explicit content (0 = no, 1 = yes)
popularity: Popularity of the song on a scale of 0 to 100
danceability: Danceability of the song on a scale of 0 to 1
energy: Energy of the song on a scale of 0 to 1
key: Key of the song (0 = C, 1 = C#/Db, 2 = D, and so on)
loudness: Loudness of the song in decibels (dB)
mode: Mode of the song (0 = minor, 1 = major)
speechiness: Speechiness of the song on a scale of 0 to 1
acousticness: Acousticness of the song on a scale of 0 to 1
instrumentalness: Instrumentalness of the song on a scale of 0 to 1
liveness: Liveness of the song on a scale of 0 to 1
valence: Valence of the song on a scale of 0 to 1
tempo: Tempo of the song in beats per minute (BPM)
time_signature: Time signature of the song (3 = 3/4, 4 = 4/4)
Jupyter Notebook
The Jupyter Notebook file spotify_song_cohort_analysis.ipynb contains the code and analysis for this project. It includes the following sections:
Data Exploration and Preprocessing
Loading the dataset
Exploring the data
Handling missing values
Encoding categorical features
Exploratory Data Analysis
Analyzing the distribution of song features
Identifying relationships between song features
Visualizing the data
Cluster Analysis
Selecting the appropriate clustering algorithm
Determining the optimal number of clusters
Performing clustering and analyzing the results
Insights and Recommendations
Interpreting the clusters and their characteristics
Providing insights and recommendations for Spotify's song cohort creation
Feel free to explore the Jupyter Notebook to understand the detailed analysis and findings of this project.
