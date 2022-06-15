# Recommendation_System
## in this this project i explore the ways to create Recommendation System 
### recommender systems can be classified into 3 types:

- Simple recommenders: offer generalized recommendations to every user, based on movie popularity and/or genre. The basic idea behind this system is that movies that are more popular and critically acclaimed will have a higher probability of being liked by the average audience. An example could be IMDB Top 250.

- Content-based recommenders: suggest similar items based on a particular item. This system uses item metadata, such as genre, director, description, actors, etc. for movies, to make these recommendations. The general idea behind these recommender systems is that if a person likes a particular item, he or she will also like an item that is similar to it. And to recommend that, it will make use of the user's past item metadata. A good example could be YouTube, where based on your history, it suggests you new videos that you could potentially watch.

- Collaborative filtering engines: these systems are widely used, and they try to predict the rating or preference that a user would give an item-based on past ratings and preferences of other users. Collaborative filters do not require item metadata like its content-based counterparts.

## i applied this concept on two different projects :
### Book Recommendations from Charles Darwin :
in this we bulid Book Recommender using Content-based  by use the book's reviews and cluster them and predict for user books from the same cluster he like 

### Find Movie Similarity from Plot Summaries :
in this we bulid movie Recommender using two ways :
- Content-based :use the movie's reviews and cluster them and predict for user books from the same cluster he like 
- Collaborative filtering engines : using Artificial neural network to predict the rating based on userid and movieid 
