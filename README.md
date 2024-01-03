# 🎥🍿 Movie Recommendation System

To provide personalized movie recommendations, this system aims to predict user ratings for films they haven't viewed. By leveraging historical data on movies and user ratings, we can forecast future ratings and index movies for suggestions. It's crucial to address real-world challenges like the "cold start problem," where new users or movies lacking historical data may pose obstacles in our prediction model.

![image](https://github.com/sruthy16/movie_recommendation_system/assets/66853359/6284b330-c968-46af-9869-83615c314811)

The recommender system integrates both content-based and collaborative filtering techniques. In the content-based approach, we employ a cosine similarity function to measure movie similarities. On the collaborative filtering side, we adopt a matrix factorization technique.

Initiating the process involves constructing a matrix factorization-based model as the first step. The output from this model, coupled with a set of carefully crafted features, serves as input for the final model. The overall procedure unfolds in three steps:

1. Develop a matrix factorization-based model.
2. Generate handcrafted features.
3. Implement the final model.

![image](https://github.com/sruthy16/movie_recommendation_system/assets/66853359/b36f8d4d-d4f7-4271-9bed-a53ec104c44f)


