You must write a project proposal and submit it by Wednesday, March 16 on Gradescope. Your  project proposal must contain the following:

###	Project goal The question you are trying to answer. If you have a hypothesis clearly state it. If you want to make a prediction describe what you are trying to predict, how do you plan to measure your success, etc.

The general theme of our project would be to explore the similarities in music. We plan to do so with its characteristics like loudness, tempo, lyrics, rhythm, and user data like reviews, playlists, and listening time.
We also plan to make predictions like:
1. Exploring genres: it recommends you to song/artist in a genre based on your liking in other genres. For eg: recommend Stop this train by John Mayer based on your high rating for Tears in Heaven by Eric Clapton.
2. Take me to the past/present: recommends artists across timelines. For eg: recommend Billie Eilish (present) from The Beatles (past).
We plan to base our success metric for predictions over the user reviews on an online forum - Rate Your Music (RYM).

####	How do you plan to collect your data?

There are 3 types of datasets that we'll be using:
1. Spotify songs dataset: consists of song metadata and characteristics like artists, release year, loudness, tempo, lyrics, rhythm, etc. This dataset will also act as our library from which the songs will be recommended. It will be retrieved from the Spotify API.
2. Spotify users dataset: this dataset will complement the above dataset - the user listening time and playlists could be a good measure to understand the nuances amongst the genres.
3. Rate Your Music dataset: this data will be scraped from rateyourmusic.com using requests and BeautifulSoup libraries. User reviews for different genres will be good heuristics for genre recommendations.

####	What challenges are you anticipating?

1. Web scraping: RYM does not offer API hence we will have to search and scrape for songs, lists, users, ratings, etc.
2. Spotify offers a lot of data in terms of attributes. Choosing the most relevant ones will be a daunting task.

####	What importance your project will have on the related field (Justify why you picked what you picked)

Current music recommendations (youtube music, Spotify song radio) are biased towards similar timelines, genres, artists. This works well to explore a particular genre. With our predictions, we can help users to explore the breadth of music.

We picked this over our other approved topic - crypto/NFT price prediction because these assets are very volatile. Their prices are subject to random bizarre events, data of which cannot be captured by high/low/open/close prices. For NFT prices too, it is difficult to get the data for the artists, wallet owners which are crucial for its price predictions. This is because of the anonymous design of blockchain. 