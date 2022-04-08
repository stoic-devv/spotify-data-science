# Building Spotify library



## Approach 1
Crawl the top 50 hits of each year since 1900s.
Might miss out on obscure genres not covered by pop culture.

## Approach 2
Get all the genres and then get the top songs in each.
Songs have multiple genres: same songs appearing in different genres.

## Approach 3
Crawl over playlists. We'll get a more diverse dataset and not just the hits.
Need playlist-ids to get the playlist contents. 

## Approach 4



## Resources;
1. getting started: https://towardsdatascience.com/how-to-create-large-music-datasets-using-spotipy-40e7242cc6a6
2. List of genres (need to crawl): https://everynoise.com/everynoise1d.cgi?scope=all