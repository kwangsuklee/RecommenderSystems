# RecommenderSystems
Two of the most popular ways to approach recommender systems are collaborative filtering and content-based recommendations. 

# collaborative filtering approach
The user is recommended items that people with similar tastes and preferences liked in the past. In another word, this method predicts unknown ratings by using the similarities between users.
Collaborative Filtering system matches persons with similar interests and provides recommendations based on this matching. Collaborative filters do not require item metadata like its content-based counterparts.

# content based filtering approach
Content Based Filtering system suggests similar items based on a particular item. This system recommends a product to a user based upon the category and description of the product. This system uses item metadata, such as genre, director, description, actors, etc. for movies, to make these recommendations. The general idea behind these recommender systems is that if a person liked a particular item, he or she will also like an item that is similar to it. 

# algorithms
This systems use matrix factorization-based algorithms such as SVD, PMF, SVD++, NMF, also, various similarity measures algorithms such as cosine similarity, MSD, pearson correlation…and many others.

# goal and plan 
My goal is to reproduce based on open datasets and open source and to implement hybrid recommendation algorithms in combination with existing recommendation algorithms and deep learning algorithms.

First, I would use the open dataset such as The Movie Lens, TMDB, Netflix for modelling the algorithm. The recommendation algorithm implementation is reproduced by modifying it based on github open source.

Second, above all, I will focus on applying deep learning. In particular, I will focus on hybrid recommendation algorithms that apply deep learning to content-based filtering or collaborative filtering.

Third, as a next step, Implementation of the algorithm would be done both from scratch as well as using libraries like Surprise library and Python Apache Spark or Apache Flink. Different implementations would be evaluated for accuracy and training efficiency. The implementation would be showcased in web using Django.
