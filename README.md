# Movie-Recommendation-System:clapper:

Content Based Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.

The Algorithm used is Nearest Neighbour algorithm-Cosine Similarity.

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api .

Check out the live demo: https://movie-recommendation-engage.herokuapp.com/ 

Link to video demo: 

## How to get the API Key?

Create an account in https://www.themoviedb.org/, click on the ```API``` link from the left hand sidebar in your account settings and fill all the details to apply for API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your ```API``` sidebar once your request is approved.

## How to Run this project?

1. Clone or download this repository to your local machine.
2. Install all the libraries mentioned in the ```requirements.txt``` file with the command pip install -r requirements.txt
3. Get your API key from https://www.themoviedb.org/. (Refer the above section on how to get the API key)
4. Replace YOUR_API_KEY in line no.7 in main.py file and hit save.
5. Open your terminal/command prompt from your project directory and run the file main.py by executing the command python main.py.
6. Go to your browser and type http://192.168.0.159:8501/ in the address bar.
 - Local URL: http://localhost:8501
 - Network URL: http://192.168.0.159:8501
7. Hurray! That's it. :tada:

## Similarity Score

How does it decide which item is most similar to the item user likes? Here come the similarity scores.

It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.

## How Cosine Similarity Works?
Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.

## Source of Datasets
[TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv)

## Requirements:
1. Python 3.9.12
2. Framework: Pycharm
3. API: TMDB
