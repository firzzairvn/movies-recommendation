
# Movies Recommendation System
This film recommendation system uses a content-based filtering algorithm which will recommend films based on the content they have.

The dataset used comes from MovieLens https://grouplens.org/datasets/movielens/25m/ which consists of 25 million rating data. Stable benchmark dataset. 25 million ratings and one million tag applications applied to 62,000 movies by 162,000 users. Includes tag genome data with 15 million relevance scores across 1,129 tags. Released 12/2019.

#### Content-based methods 
are quick to compute and easy to understand. Additionally, they can be efficiently adapted to new items or users. However, one of the major limitations of content-based recommendation systems is that the model only learns to recommend items similar to those the user is already using or, in our case, listening to. While this can be useful, the value of such recommendations is significantly reduced because it lacks the element of surprise that comes with discovering something entirely new.

In this repository there are files:
- dataset-preparation.ipynb 
- model.ipynb 

In the dataset-preparation.ipynb file, here we prepare the initial dataset which we use from the website https://grouplens.org/datasets/movielens/25m/ to take several columns from the dataset provided. for the dataset finally we have a dataset with columns movieId, title, genre, tag, rating, year and content.

In the model.ipynb file, here we use a content-based filtering algorithm to create a model that will recommend movies based on the "content" column in the dataset. This model uses Term Frequency - Inverse Document Frequency (TF-IDF). This model measures how important a term is in a document compared to a collection of documents. Then there is cosine similarity which measures the similarity between two inner product space vectors. 




## Dependencies
You can choose the latest versions of any of the dependencies below:

- scikit-learn
- pandas
- re
- numpy

or you can directly run the file in requirements.txt <code> pip install -r requirements.txt </code>
