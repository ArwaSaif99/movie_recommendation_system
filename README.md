# Movie Recommendation System

This project implements a movie recommendation system using the Alternating Least Squares (ALS) algorithm. The system is trained and evaluated on the MovieLens-32M dataset. It starts with a **bias-only model** and evolves to incorporate **latent factors** for improved prediction accuracy.

## Features

- **Bias-Only Model**: A baseline model that only uses biases for users and movies.
- **Matrix Factorization Model**: Enhances the baseline model by introducing latent factors to improve recommendations.
- **RMSE and Loss Metrics**: The system tracks performance using **Root Mean Squared Error (RMSE)** and **Loss**.
- **Movie Recommendations**: The system generates movie recommendations based on user preferences.
- **2D Embeddings**: Visualization of movie latent trait vectors in a 2D space to explore movie relationships.

## Model Performance

The system evaluates its performance based on the following metrics:

- **Root Mean Squared Error (RMSE)**: Measures the average magnitude of the prediction error.
- **Loss**: Total prediction error, used to evaluate model fit.

### Results

#### Bias-Only Model:

- Training RMSE: 0.84
- Test RMSE: 0.87

#### Matrix Factorization Model:

- Training RMSE: 0.61
- Test RMSE: 0.79

## Visualizations

- **2D Embedding Plot**: Latent movie vectors are embedded in a 2D space to visualize the relationships between movies. The plot shows similar movies clustered together, helping to assess the model's ability to group movies based on latent features.

## Conclusion

This movie recommendation system demonstrates the effectiveness of the **Alternating Least Squares (ALS)** algorithm in predicting user preferences. By incorporating latent factors in the matrix factorization model, the system offers more personalized and accurate recommendations compared to the baseline bias-only model.

## Future Work

Future improvements could focus on:

- **Hybrid Models**: Combining collaborative filtering and content-based filtering to enhance recommendation quality.
- **Handling Cold Start**: Addressing the cold-start problem by incorporating more metadata for new users or movies.
