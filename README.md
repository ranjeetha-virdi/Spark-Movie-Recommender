

![Screenshot 2023-11-04 155311](https://github.com/ranjeetha-virdi/Movie-Recommender/assets/81987445/54bef2b4-c5d0-47e7-8121-a04082a3d540)






## Movie Recommender:
This a movie recommender system developed by using Spark to recommend movies similar to the movie name and movie ID provided by a user.


## Recommendation Model:
A recommendation model, is an algorithm that aims to provide the most relevant and relatable information to a user depending on the behaviour of the user.

## Collaborative Filtering:

Collaborative filtering tackles the similarities between the users and items to perform recommendations. Meaning that the algorithm constantly finds the relationships between the users and their likes and in-turns does the recommendations based on similarities between the movies they like. The algorithm learns the embeddings between the users. The most common technique is by performing cosinesimilarity function to find the similar movies that make up the interest of a particular set user of users based on their ratings. Once cosinesimilarity is calculated we will define a quality threshold to sort movies based on these scores.


