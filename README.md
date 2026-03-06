# Music Recommender
This was an early project from my "Algorithms for Machine Learning" class.  
Originally completed 10/16/2025.

## Project Goal
The goal of the project was to create a recommender algorithm that I can personally use to recommend music to friends based on key words.

### Research Outline
This project uses natural language processing (NLP) and latent dirichlect allocation (LDA) to group and identify topics found in the music I listen to.  
#### Training  
The Spotify Million Song Dataset from Kaggle was used to train the algorithm.  
#### Application  
The trained algorithm was applied to the songs.csv dataset, which was collected from my recent listening.

## Files Overview
**Music_Recommender.ipnyb -**  Includes the full code used to clean the data, train the NLP and LDA, and then apply it to my own data. 
<br> 
**songs.csv -**  Data collected from my own listening. This data is plugged into the trained program to create personalized recommendations.
<br>
_Not In Folder:_ **spotify_millsong_data.csv -** Spotify Million Song Dataset from Kaggle. The dataset can be found [here](https://www.kaggle.com/datasets/notshrirang/spotify-million-song-dataset, 'Spotify Million Song Dataset'). This dataset records the artist, title, and lyrics of over 50,000 songs. It is used to train the algorithm.

## Further Research
Despite the size of the training dataset, it still contains a fairly limited range of music. The program may benefit from more specialized datasets to counteract the limits of the musical range without creating a realiance on extremely large training datasets. The output of the recommender is still fairly limited and may benefit from assistance of a support vector machine to provide ranking levels for the topics correlated for each song.
