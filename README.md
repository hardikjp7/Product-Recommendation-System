# Recommendation System for E-commerce

This Jupyter Notebook presents a comprehensive recommendation system for an e-commerce platform, covering various aspects of recommendation techniques.

## Part I: Popularity-Based Recommendation

Popularity-based recommendation systems are effective for targeting new customers with popular products. The notebook analyzes Amazon Beauty product ratings, identifies popular products, and visualizes them.

## Part II: Model-Based Collaborative Filtering

This section implements a model-based collaborative filtering system. It leverages the Truncated Singular Value Decomposition (SVD) technique to identify patterns based on user preferences. The notebook recommends products to users based on purchase history and similarity of ratings.

## Part III: Text-Based Recommendation

For businesses without user-item purchase history, a search engine-based recommendation system is designed. It recommends products based on textual clustering analysis given in product descriptions. The system uses K-Means clustering on TF-IDF vectorized product descriptions to group similar products.

### Installation

Ensure you have the required Python libraries installed:

```bash
pip install numpy pandas matplotlib sklearn
```

### Usage

1. **Run the Popularity-Based Recommendation Section:** Execute the code related to Part I for analyzing and visualizing popular products.

2. **Run the Model-Based Collaborative Filtering Section:** Execute the code for Part II to build a model-based collaborative filtering system.

3. **Run the Text-Based Recommendation Section:** Execute the code for Part III to create a search engine-based recommendation system.

4. **Custom Recommendations:** Utilize the provided function `show_recommendations` to generate product recommendations based on key search words.

### LinkedIn

Connect with me on LinkedIn: [![LinkedIn](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=linkedin&colorB=2867B2)](https://www.linkedin.com/in/your-linkedin-profile)

Feel free to adapt and customize the code according to your specific business requirements. This recommendation system is designed to offer flexibility and effectiveness in providing recommendations to users with or without purchase history.
