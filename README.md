# Problem Statement:
Predicting an artist’s popularity based on different independent variables like artists, popularity, Acousticness, Danceability, Duration_ms, Energy, Instrumentalness, liveness, loudness, speechiness, temp, key, valence, mode, and count.
Data: At the end of each year, Spotify compiles a playlist of the songs streamed most often over the course of that year. This year's playlist (Top Tracks of 2018). The question is: What do these top songs have in common? Why do people like them?
Original Data Source: The audio features for each song were extracted using the Spotify Web API and the Spotify Python library. Credit goes to Spotify for calculating the audio feature values.
**Data Description:** There is one .csv file in the dataset. (top2018.csv) This file includes:
•	Spotify URI for the song
•	Name of the song
•	Artist(s) of the song
•	Audio features for the song (such as danceability, tempo, key, etc.)
•	A more detailed explanation of the audio features can be found in the Metadata tab.
The data set consists of 27622 observations. Where it contains 13 columns and 27622 rows. We considered the artist’s popularity as our response variable and the other 12 as independent variables.

**Source of data:**  Kaggle
**Software used:** Python
