# Final report



## Data Extraction

Existing analyses on music data almost exclusively uses Spotify data due to their rich [API collections](). For our project, we decided to collect the data from multiple sources. It was one of our assumption that this would complement the Spotify data to give us better results. We validate this assumption later in the analysis.

### RateYourMusic Data

[RateYourMusic]() is a social platform where its users review their music. It's a large community with more than 0.5 million users, and an average of 332 reviews per album. It also curates the lists of top albums' every year/per genre based on these reviews.

With our project goal to increase the genre pallette of a listener, RYM community helps us cover a breadth of genres compared to Spotify, which mainly focus on the listener's history and is more skewed towards pop genres. Also, the data for ratings, reviews and number of reviews will provide us as a metric for our song recommendation. 

We customized our scraper over an open-source project [rymscraper](). We collected the top 20 albums of every year starting from 1960. 

`['rym rating', 'ratings', 'reviews']`

### Spotify Data

[Spotify]() is the largest music streaming platform with around 500 million users and largest song library. The Spotify Web API provide data about music artists, albums, and tracks, directly from the Spotify Data Catalogue.

For retrieving the data we used [spotipy](), a Python library wrapper over Spotify's APIs. Here are some features that we extracted:

```
Audio features:
'danceability', 'energy', 'key', 'loudness', 'mode',
'speechiness', 'acousticness', 'instrumentalness', 'liveness',
'valence', 'tempo', 'type', 'uri', 'duration_ms', 'time_signature',

Song metadata:
'id', 'name', 'album', 'date', 'genres', 'track_href', 'analysis_url', 'popularity'

```

## Preparing dataset

### Searching for songs 
### Threshold for album

### Merging datasets

## Challenges

## Cleaning dataset

### Finding top k genres

### Assumptions

### Selecting top n features