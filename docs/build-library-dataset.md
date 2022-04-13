# Building Spotify library

## Available datasets
1. https://www.kaggle.com/datasets/iamsumat/spotify-top-2000s-mega-dataset 
2. top 100 from 1921-2020: https://www.kaggle.com/datasets/ektanegi/spotifydata-19212020
3. multi-genre playlists data: https://www.kaggle.com/datasets/siropo/spotify-multigenre-playlists-data 


## Approach 1
Crawl the top 50 hits of each year since 1900s.
Might miss out on many genres since the top albums cover a fewer genres

## Approach 2
Get all the genres and then get the top songs in each.
Songs have multiple genres: same songs appearing in different genres.

## Approach 3
Crawl over playlists. We'll get a more diverse dataset and not just the hits.
Need playlist-ids to get the playlist contents. 

## Implemented approach
1. Get top albums from 1950-2021 from RYM
2. Search and fetch the songs in it from Spotify
3. Merge the datasets



## Resources;
1. getting started: https://towardsdatascience.com/how-to-create-large-music-datasets-using-spotipy-40e7242cc6a6
2. List of genres (need to scrape): https://everynoise.com/everynoise1d.cgi?scope=all
3. Spotify query: https://developer.spotify.com/documentation/web-api/reference/#/operations/search


## Knowledge dump
1. https://www.kaggle.com/code/shwetagoyal4/spotify-song-eda
2. https://adriancaruana.com/rym.html
3. https://ericboam.medium.com/i-decoded-the-spotify-recommendation-algorithm-heres-what-i-found-4b0f3654035b 