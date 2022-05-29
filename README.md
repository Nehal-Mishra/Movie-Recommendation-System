# Movie-Recommendation-System

Content Based Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api .

Check out the live demo: https://movie-recommendation-engage.herokuapp.com/ 

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
7. Hurray! That's it.
