# Restaurant-recommender

**Restaurant Recommender using Truncated SVD, Cosine Similarity, and Naive Bayes**

This project implements a restaurant recommendation system that utilizes a combination of machine learning techniques to provide personalized restaurant suggestions, recommend similar restaurants, and predict user sentiment based on new reviews. The system is built using Python and Jupyter Notebook.

**Features:**

1. **Truncated SVD Model for Rating Prediction:**
   - The Truncated Singular Value Decomposition (SVD) model is employed to predict user ratings for restaurants.
   - It reduces the dimensionality of the user-restaurant rating matrix, capturing latent factors that influence user preferences.
   - The model learns patterns from existing user ratings and predicts potential ratings for unvisited restaurants.

2. **Cosine Similarity Model for Similar Restaurant Recommendations:**
   - The Cosine Similarity model suggests restaurants similar to the user's past preferences.
   - User preferences and restaurant features are transformed into numerical vectors.
   - The cosine similarity between user vectors and restaurant vectors is calculated to identify similar restaurants.

3. **Naive Bayes Model for Sentiment Prediction:**
   - The Naive Bayes model predicts sentiment polarity (positive/negative) of new user reviews.
   - It analyzes the text of the reviews and assigns a sentiment label.
   - This helps in understanding user sentiments and improving the quality of recommendations.

**How to Use:**

1. Install the required libraries mentioned in the `requirements.txt` file.
2. Run the Jupyter Notebook to explore the system's functionality.
3. Provide user preferences, such as favorite cuisines and location, to generate personalized restaurant recommendations.
4. Get similar restaurant recommendations based on previously visited restaurants.
5. Predict sentiment polarity for new user reviews to enhance the system's understanding of user preferences.

**Note:**
- The data used for this project should be appropriately formatted and preprocessed to match the system's input requirements.
- Customize the model parameters and data preprocessing steps according to your use case and data characteristics.
- Please be aware that the dataset required for running this project is not provided within this repository. Instead, you can access the dataset through the provided link (https://www.kaggle.com/datasets/choonkhonng/malaysia-restaurant-review-datasets).

**Dependencies:**

The project relies on the following libraries (specified in `requirements.txt`):
- numpy
- pandas
- scikit-learn

Feel free to adapt and enhance this project for your specific needs. Happy recommending and predicting user preferences and sentiments!
