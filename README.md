# Weratedogs data wrangling

The Weratedogs twitter data archive was used for our research purpose. Provided was the enhanced twitter archive that contained over 2000+ of tweets with their ratings as well as the image predictions tsv file that was provided using a neural network project.

# Summary of data wrangling process
step1: Load these different sources of data programmatically into the notebook
step2: Query the twitter API using tweepy that provided additional information for the dataset such as retweet_count, and the favorite_count. To do this, you might need build an app using the twitter's API and generate user secrets(Obtain approval for a twitter developer's account)
step3: Queried the API using the tweet IDs in the archive and wrote the data into a .txt document.
Step4: Used the readlines method to read the data line by line into a pandas dataframe.
Step5: Clean the data
Step6: Visualize and analyse the data

