# Movie-Recommendation-System
A movie recommendation system, or a movie recommender system, is an ML-based approach to filtering or predicting the users’ film preferences based on their past choices and behavior. It’s an advanced filtration mechanism that predicts the possible movie choices of the concerned user and their preferences towards a domain-specific item, aka movie.

The primary goal of movie recommendation systems is to filter and predict only those movies that a corresponding user is most likely to want to watch. The ML algorithms for these recommendation systems use the data about this user from the system’s database. This data is used to predict the future behavior of the user concerned based on the information from the past.

There are 3 types of Recommendation System
 
 **1) Content based Recommendation System**
  
Content-Based Recommendations systems are the systems that look for similarity before recommending something The similarity of different movies is computed to the one you are currently watching and all the similar movies are recommended to us.
    
    
  **2) Collaborative filtering based Recommendation System**

  Collaborative filtering tackles the similarities between the users and items to perform recommendations. Meaning that the algorithm constantly finds the relationships between the users and in-turns does the recommendations. The algorithm learns the embeddings between the users without having to tune the features.
  
  
  **3) Hybrid Recommendation System**
  
  A hybrid recommendation system is a special type of recommendation system which can be considered as the combination of the content and collaborative filtering method.
  
  
  
***In this project we mainly focus on Content based recommendation system***


The similarity is the main key fundamental in the case of content-based recommendation systems. A most similar thing to what we are currently watching gets recommended to us.

**Euclidean Distance**

This distance metric is used when we have numeric data. For example, if I want to compute the similarity between One plus 6 and other one plus variants based on ram and camera. The values of ram and camera for each variant would be in numbers. In these cases, we calculate Euclidean distance if the results of this distance come out to be 0 then both the two are considered to be similar whereas if the distance is anything other than 0 then are not similar. 

**Cosine Similarity**

This type of metric is used to compute the similarity textual data. Consider an example where we have to find similar news or similar movies. How is it done? We convert these textual data in the form of vectors and check for cosine angle between those two vectors if the angle between them is 0. It means they are similar or else they are not. Most used similarity measures when we talk about the similarity between any textual content. There are other different metrics as well like Jaccard Similarity that is used when we have categorical data. 
