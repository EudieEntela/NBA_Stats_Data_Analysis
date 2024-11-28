# Final Capstone Project Proposal Outline

EUDIE ENTELA - Final Capstone Project Proposal Outline 

## I. Introduction

- There is so much flexibility with music data and patterns that can be found. I intend to find some underlying patterns and trends within the data using Spotify's API and Genius' API for lyrics. The thing about EDA is that you dont always know what you are going to find and that, I believe is part of the fun. It can reveal different trends, preferences and popularity in all different types of music genres.

## II. Project Objective

- The primary goal is to try and find relations between song lyrics and the song features. How do they correlate? Do song lyrics play a part in a songs popularity? Is there a common theme with lyrics in top songs? Are there any correlations between lyrics across different music genres? What trends in music follow the seasons or the mood year round? What type of songs tend to have more of a positive sentiment vs a negative sentiment and have are the factors that influence them? (I could add more questions)
  
## III. Data Description

- I plan on using the Spotify API in order to gather data for songs, artists and albums (tempo, energy, danceability, popularity). I will also use Genius' API in order to gather lyrics for certain songs to analyze.
- https://developer.spotify.com/ & https://docs.genius.com/
- Spotify's Web API provides data in a JSON format. This is structured in a series of nested objects and arrays. It includes detailed information on audio features and descriptive information on songs, artist and albums.

## IV. Methodology

- I'll start by retrieving song, playlists and audio features from Spotify's API. I'll get a larger dataset from various different playlists and albums: (import spotipy in order to do this, I will need my Spotify client token)
- I'll then retrive lyrics for the songs using Genius' API. Using the track ID and track name, i can match it with genius' data (import lyricsgenius, i will need my Genius client token)
- Then, I'll clean the dataset (Missing/Null data and possibility combining columns depending on common themes)
- After that, I'll do a deep EDA with the data: Analyzing song lyrics, audio features, and sentiment analysis (TextBlob) and try and find correlations between them.
-Lastly, I'll build an interactive interface (Streamlit) where the user is able to explore features themselves.

## V. Expected Deliverables

- A user interactive page where they will be able to search for lyrics, songs, popularity scores, etc and explore the correlation and relationship between them.
- A NoteBook with step-by-step of my findings and visualizations
- A Powerpoint presentation summarizing my findings and my overall work done on the project

## VI. Timeline and Tasks

- Starting with Jupyter NoteBook, import Spotify and Genius API, gather initial data, process and clean the data (Shouldn't take too much time)
- Analyze lyrics for songs and try perform word embedding and also classify using sentiment analysis
- EDA on audio features, song information and lyrics (Will spend a decent amount of time with visualizations)
- Find correlations between lyrics and song features
- Complete interactive page for user (Will most likely take the most time)
- Complete powerpoint on findings and work
  
## VII. Potential Challenges

- Lyrics from Genius: A lot of songs may not have lyrics, I will have the handle any missing values. I will also have to process the lyrics and remove unneeded characters.
- API Rate Limits: I had trouble with my project for M7 because I would run my code a lot and would hit the rate limit. And that would delay my progress because i had to wait about an hour for it the reset.
- Interactive Page: Although I believe this will be fun, being that it is a new application, it will take a while before i get used to it and I may encounter some problems that I am not familiar with.
