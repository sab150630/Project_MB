# Project_MB
# Text Mining using SQL

This script explodes the description text from the Airbnb listings data set to word list. The word list is then used to calculate word frequency, TFIDF (Term Frequency–Inverse Document Frequency) and find bigrams (word pair) and bigram frequency. Using frequency to find words/word pairs with highest review rating.

Data Source -
https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data

Steps:-
Data Loading (Importing Airbnb listing data)
Data Cleaning (Treating NULLS and removing unwanted signs/symbols)
Exploring dataset using Tableau (https://public.tableau.com/profile/megha.bhatnagar#!/vizhome/NYCAirbnbMichelinStarResturants/RoomType)
Data Wrangling (Explode description text into wrod list, calculate TFIDF, create bigrams)
Aggregation (Aggregating TFIDF scores for word/word pairs)
Analyzing ( Linking words/word pairs to high review rating)
Visualizing (https://public.tableau.com/profile/megha.bhatnagar#!/vizhome/TextMining_15931414705560/Description)
