# Instagram-Recommendation-with-ML
**Using Machine Learning to make  Recommendations for Instagram posts.**

This machine learning project is an Instagram recommendation system that uses Python to recommend posts to a user based on the similarities to the post the user just interacted with. The project works as follows:

## Importing Required Libraries and Dataset

The first step of the project is to import the required libraries such as pandas, numpy, sklearn, and Google Colab. Additionally, the dataset for the model is also imported using pandas.

## Selecting Required Columns

In this step, the required columns of the dataset are selected, which in this case are caption and hashtags.

## Finding Similarities between Captions

In order to recommend posts, the project uses cosine similarity in machine learning to find similarities between captions. This is achieved by using the TfidfVectorizer and cosine_similarity methods from the sklearn library.

##Creating a Recommendation System

After finding similarities between posts, the recommendation system recommends them to the user based on the similarities to the post the user just interacted with. The recommended posts are generated using the recommend_post function, which returns the top 5 recommended posts for the user.

## Results

The final step of the project is to print the recommended posts for a user. The recommended posts are printed using the "Recommended Post" column from the dataset.

This project is an excellent example of how machine learning can be used to enhance user experience in social media applications. By using a recommendation system, users are provided with personalized content, which increases engagement and satisfaction with the application.
