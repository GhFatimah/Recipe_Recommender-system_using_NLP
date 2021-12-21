# Recipe_Recommender-System_Using_NLP

The goal of this project is to build content-based recommender system using NLP. The recipes of AFA is a recommendation system with content-based filtering methods to generate recipes that have something in common in terms of the  ingredients.


### Dataset:

The dataset contains around 40,000 recipes scrapped from Allrecpies.com (Kaggle). Each recipe entry contains a recipe title, a list of ingredients and measurements, instructions for preparation and a picture of the final result.


### Algorithms:

1- Data Preprocessing:

Various preprocessing steps were used such as: tokenization, remove punctuation mark and digits and remove stop words that were created based on the proposed model.

2 - Vectorization : Count Vectorizer and TF-IDF Vectorizer

3 - Matrix factorization: LSA and NMF

4 - Cosine similarity


### Tools:

- Numpy and Pandas for data manipulation
- Scikit-learn for modeling
- Matplotlib and Seaborn for plotting
- NLTK and Gensim for topic modeling
