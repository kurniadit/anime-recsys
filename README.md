
# <p align="center">Anime Recommendation System</p>

## Background
  
The world of anime boasts an extensive and diverse catalog of series, movies, and OVAs, spanning various genres, themes, and styles. With thousands of titles available, users can easily become overwhelmed when trying to discover new content. In today's digital landscape, users have grown accustomed to personalized experiences. A recommendation system can tailor anime suggestions based on individual user preferences, ensuring that viewers are presented with content that aligns with their interests. By offering personalized recommendations, anime streaming platforms can significantly enhance user engagement. Users are more likely to spend time on a platform that consistently introduces them to anime they find appealing, increasing their overall satisfaction. 

So, we will create a recommendation system to meet user needs, especially on the anime platform. However, there are several considerations before we develop the recommendation system model, including:

1. The data we have consists of user interactions with anime as items, where these interaction values represent user ratings for anime. Therefore, the task at hand is to predict anime ratings, especially for anime that have not been rated by users before.

2. The recommendation system model we are building is a personalized recommendation system because all the data we have is from users who have interacted with items, and we do not assume the occurrence of a cold start problem.

3. The chosen approach for creating the recommendation system model with a rating prediction task is the Funk SVD method. The reason for selecting this approach is that it takes into account the roles of both users and items (collaborative filtering), as opposed to content-based approaches. Additionally, from a mathematical standpoint, this method has an objective function that can be optimized when compared to neighborhood collaborative filtering approaches.



    