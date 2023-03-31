![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Lab | Unsupervised learning intro (GNOD - part 4)

#### Instructions 


It's the moment to perform clustering on the songs you collected. Remember that the ultimate goal of this little project is to improve the recommendations of artists. Clustering the songs will allow the recommendation system to limit the scope of the recommendations to only songs that belong to the same cluster - songs with similar audio features.

The experiments you did with the `Spotify` API and the PopVortex web scraping will allow you to create a pipeline such that when the user enters a song, you:

1. Check whether or not the song is in the PopVortex Hot 100.
2. Collect the audio features from the `Spotify` API.

After that, you want to send the `Spotify` audio features of the submitted song to the clustering model, which should return a cluster number.  Then you recommend a song from the same cluster number.

We want to have as many songs as possible to create the clustering model, so you should get a  bigger dataset available on Kaggle containing more songs with audio features that have already been scraped and saved as a .csv file.  Here are some links to try:
[Datasets 1960 my - 2019](https://www.kaggle.com/datasets/theoverman/the-spotify-hit-predictor-dataset?select=README.txt)
[Datasets 1921 - 2020](https://www.kaggle.com/datasets/yamaerenay/spotify-dataset-19212020-600k-tracks?select=tracks.csv)
