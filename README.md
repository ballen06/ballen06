# Ben Allen in collaboration with Vaibhav Chaudari
For our project, we used three separate data sources to evaluate several factors related to song, artist, and overall music popularity. A json file of Spotify top charts, a csv file of artist streaming statistics, and another csv file containing adjacent artist and song information were all used to perform data analysis on our research question. 

The json file (spotify_songs_data) contains the top 2000 songs from 2000-2019 with descriptive elements like key, danceability, energy, acoustics, genre, etc. in addition to a ranked year by year list with song and artist names. In addition to simply evaluating these song ranks during each year in this time period, these data can be used to gauge the music characteristics most often associated with the Spotify top charts, if we are to perform correlation analysis. 

The artist streaming csv (artist_stat) contains statistical information like streams, features, tracks, and number of songs that have passed 1 billion / 100 million streams. Building upon the data from the previous section, this data can be used to contextualize the ranked charts by allowing us to visualize artist popularity over time through several raw streaming measures. 

The additional csv (artist_spotify) contains a few key measures, namely followers, popularity score (scale 1-100), and genre, each of which was used in conjunction with the artist streaming data to provide a clear picture of the popularity of artists and song genres during our time period. 

These data were used to investigate a different piece of analysis, regarding the popularity of artists, songs, and music characteristics that have dominated the music market over the past 20 years.  Several pre-processing steps were necessary upon loading in our files to clean the data in preparation for analysis.

