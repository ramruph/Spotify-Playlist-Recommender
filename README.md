# Spotify-Playlist-Recommender
Utilizing Unsupervised K-Mean Algorithm and Principal Component Analysis to determine similar songs from a Spotify dataset sourced thorugh Kaggle
# Overview

The goal of this project is to examine and predict groupings of songs within a given Spotify playlist by employing machine learning methodologies such as K-means clustering and Principal Component Analysis (PCA). Through identifying patterns and associations in the musical attributes, the algorithm can form song groupings that exhibit similar qualities, allowing for the generation of customized playlists tailored to users' preferences and listening patterns.

The main objective of this project is to improve user experience on Spotify designing playlists that align with user;s unique tastes. This project seeks to pinpoint song groupings that can serve as the basis for assembling playlists with a consistent theme or genre. This approach not only contributes to a more enjoyable and engaging listening experience for users, but it also benefits artists and content creators by introducing their music to an audience whose preferences align with their work.


# Results

The Results from utilizing the K-means clustering algorithm on Spotify data to predict playlists based on the cluster a song falls into has proven to be effective to the point where we can create a general playlist of similar songs. With an inertia score of 810,265.351, a PCA of 6, and a K value of 5, we were able to generate distinct song clusters that can be leveraged to create tailored playlists for users. The combination of dimensionality reduction through PCA and the K-means algorithm has allowed us to uncover underlying patterns in the data, resulting in more personalized and accurate playlist recommendations. Because this is an unsupervised model, unlike a supervised model, there is not a true way to determine the real accuracy of these playlists. 


# Conclusion

With a siloutee score of 0.22, this model has a lot of room for imporvements. The current project leveraged unsupervised machine learning techniques such as K-means clustering and PCA to predict song clusters from a Spotify song dataset, resulting in personalized and engaging playlists for users based on musical attributes. However, there is potential for further improvement and exploration in the future by incorporating additional techniques and strategies to get the clusters more accurate. Some further development of this model for more accurate classifications are implementing more advance techinques or more detailed data.
