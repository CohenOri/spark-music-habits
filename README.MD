### Spark Solution for lastfm-dataset-1K challenge :)
#### Solution can be found at [Solution Notebook](music_habits.ipynb)
Since its pure batch solution - Spark is more suitable than Flink.

Challenge:
Go to the following URL, and download the dataset on sampled Last.fm usage: 
http://www.dtic.upf.edu/~ocelma/MusicRecommendationDataset/lastfm-1K.html 
Provide a Spark based solution.

Part A 
Create a list of user IDs, along with the number of distinct songs each user has played. 

Part B 
Create a list of the 100 most popular songs (artist and title) in the dataset, with the number of times 
each was played. 

Part C 
Say we define a user’s “session” of Last.fm usage to be comprised of one or more songs played by that  user, where each song is started within 20 minutes of the previous song’s start time. 
Create a list of the top 10 longest sessions, with the following information about each session: userid, timestamp of first and last songs in the session, and the list of songs played in the session (in order of play).