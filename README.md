# NetFlix_Movie_Recommendation

Netflix is all about connecting people to the movies they love. To help customers find those movies, they developed world-class movie recommendation system: CinematchSM. Its job is to predict whether someone will enjoy a movie based on how much they liked or disliked other movies. Netflix use those predictions to make personal movie recommendations based on each customer’s unique tastes. And while Cinematch is doing pretty well, it can always be made better.

Now there are a lot of interesting alternative approaches to how Cinematch works that netflix haven’t tried. Some are described in the literature, some aren’t. We’re curious whether any of these can beat Cinematch by making better predictions. Because, frankly, if there is a much better approach it could make a big difference to our customers and our business.


Data
Get the data from : https://www.kaggle.com/netflix-inc/netflix-prize-data/data

Data files :

combined_data_1.txt </br>
combined_data_2.txt </br>
combined_data_3.txt </br>
combined_data_4.txt </br>
movie_titles.csv </br>

The first line of each file [combined_data_1.txt, combined_data_2.txt, combined_data_3.txt, combined_data_4.txt] contains the movie id followed by a colon. Each subsequent line in the file corresponds to a rating from a customer and its date in the following format: </br>

CustomerID,Rating,Date </br>
MovieIDs range from 1 to 17770 sequentially. </br>
CustomerIDs range from 1 to 2649429, with gaps. There are 480189 users. </br>
Ratings are on a five star (integral) scale from 1 to 5. </br>
Dates have the format YYYY-MM-DD. </br>
