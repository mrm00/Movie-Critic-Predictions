This repository uses Bayesian inference (specifically Naïve Bayes) to perform text analysis on a subset of movie reviews from Rotten Tomatoes database. I use sci-kit learn’s CountVectorizer package to transform quotes into a sparse matrix to which a Multinomial Naïve Bayes model is applied. The purpose of this model is to predict (based off of a movie quote) whether the critic rated the movie as fresh or rotten.
