# Restaurant Recommendation System Project

## Overview
This project implements and compares different recommendation system approaches for restaurants in Buenos Aires, with a focus on serving college students' dining needs. The project evolved through three main phases, each building upon the previous one to create increasingly sophisticated recommendation systems.

## Document Contents

### 1. Content Based
The first phase focused on implementing a content-based recommendation system. Key components include:
- Initial data collection and preprocessing of restaurant data
- Implementation of content-based filtering using:
  - Feature normalization
  - TF-IDF text processing for restaurant descriptions
  - One-hot encoding for categorical data
  - Cosine similarity calculations
- Performance evaluation using precision@K and recall@K metrics
- Visualization of restaurant data distributions and patterns

### 2. Collaborative Filtering for Individuals
The second phase expanded the system to include collaborative filtering approaches:
- Implementation of memory-based collaborative filtering:
  - User-based collaborative filtering
  - Item-based collaborative filtering
- Development of model-based collaborative filtering using SVD
- Comprehensive comparative analysis of different approaches
- Hyperparameter tuning for optimal performance
- Extended evaluation metrics including MAE and RMSE
- Enhanced data processing with increased dataset size

### 3. Collaborative Filtering for Groups
The final phase adapted the system to handle both individual and group recommendations:
- Modified content-based and collaborative filtering for group scenarios
- Implementation of group profile creation and aggregation methods
- Comparative analysis between individual and group recommendation performance
- Integration of previous approaches into a unified system

## Key Features
- Multiple recommendation approaches: content-based, collaborative filtering, and hybrid methods
- Support for both individual and group recommendations
- Comprehensive evaluation metrics and performance analysis
- Focus on practical applications for college students

## Technical Implementation
The system is implemented in Python, utilizing:
- pandas for data manipulation
- scikit-learn for machine learning operations
- TF-IDF for text processing
- SVD for dimensionality reduction
- Custom evaluation metrics
- Visualization tools including matplotlib and seaborn

## Evaluation Results
The system was evaluated using multiple metrics:
- Precision@K and Recall@K for recommendation relevance
- MAE and RMSE for rating prediction accuracy
- Comparative analysis across different approaches
- Specific performance metrics for group recommendations

## Applications
The methodology has been successfully applied to:
- Restaurant recommendations for individuals
- Group dining suggestions
- Professional networking (InternLink project)

## Tutorials
Mwenjwa, N. (2025). Content-Based Restaurant Recommendation System. [[Technical report](https://medium.com/@joymwenjwa/content-based-restaurant-recommendation-system-7a7cad24d979)].

Mwenjwa, N. (2025). Collaborative Filtering Restaurant Recommendation System. [[Technical report](https://medium.com/@joymwenjwa/collaborative-filtering-restaurant-recommendation-system-cb333aecd7e4)].

## Sources
Bhattacharyya, M. (2022, December 7). Metrics of Recommender Systems. *Towards Data Science*. https://towardsdatascience.com/metrics-of-recommender-systems-cde64042127a

Javed, M. (2020, November 4). Using Cosine Similarity to Build a Movie Recommendation System. *Towards Data Science*. https://towardsdatascience.com/using-cosine-similarity-to-build-a-movie-recommendation-system-ae7f20842599

Vatsal. (2021, November 3). Recommendation Systems Explained. *Towards Data Science*. https://towardsdatascience.com/recommendation-systems-explained-a42fc60591ed

Wikipedia Contributors. (2019a, March 3). Cosine similarity. *Wikipedia*. https://en.wikipedia.org/wiki/Cosine_similarity

Wikipedia Contributors. (2019b, September 7). Spearman's rank correlation coefficient. *Wikipedia*. https://en.wikipedia.org/wiki/Spearman%27s_rank_correlation_coefficient