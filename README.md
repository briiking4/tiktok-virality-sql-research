# sql-project

Project Name: What makes a song go viral?: An Exploration of TikTok Songs and Billboard's Top Charts

Project Objective:

As TikTok emerges as one of the biggest influences on music today, small artists have increasingly gained popularity like never before. However, these small to medium
sized artists are faced with the problem: Why aren't people interested in my music after I have gone viral? How can I utilize TikTok to gain visibility in mainstream music?
To solve this problem, I am conducting a comprehensive audio and features analysis on what makes a song go viral on TikTok and comparing these songs to Billboard's Hot List. Billboard's Hot List
is the industry's standard Top Charts list. This will allow me to gain insight on how an artist can transend beyond TikTok and onto the Charts. 



This project focuses on uncovering actionable insights on playlists and charts in order to understand how to leverage the leading platform influencing music today: TikTok. 


Data: 

To collect my data I fetched information from Spotify's api on two playlists: Billboard Hot List by Billboard, and TikTok Hits by TikTok. Both of these playlists are current and updated weekly.
Within Spotify's api, I was able to fetch information about the track, its audio features, and the artist. The audio features object contains insight such as the tracks tempo, danceability,
energy etc. The track and artist information provided insight on their respective popularity through an index created by Spotify through a combination of different factors including number of streams.


Notebooks:

Data Collection: This notebook fetches data from Spotify's api, creates dataframes, and inserts them into ny database. 
LINK: [https://github.com/briking4/sql-project/blob/bc4bafdb4cf1ae2601cc622c5f26906a5cc10aae/data_collection.ipynb
](https://github.com/briiking4/tiktok-virality-sql-research/blob/main/data_collection.ipynb)
SQL Analysis: This notebook contains questions I have asked of my data, conducts exploratory SQL, and analyzes the results.  
LINK: [https://github.com/briking4/sql-project/blob/bc4bafdb4cf1ae2601cc622c5f26906a5cc10aae/sql_analysis.ipynb
](https://github.com/briiking4/tiktok-virality-sql-research/blob/main/sql_analysis.ipynb)

Presentation: This notebook contains a combination of the two noteabooks to create presentation slides. 
LINK: [https://github.com/briking4/sql-project/blob/bc4bafdb4cf1ae2601cc622c5f26906a5cc10aae/presentation.ipynb
](https://github.com/briiking4/tiktok-virality-sql-research/blob/main/presentation.ipynb)
Future Improvements:
  1. I would add genre as a table to be able to group these tracks by genre. Given that spotify has no clear list of genres and has a lot od them, it was very dificult
  to include at the moment. 
  2. I would extract a much larger dataset and hopefully be able to gain access to historical data rather than what is currently trending. 
