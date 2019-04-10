# Winerama  
###### a web recommender tutorial using Python, Django, and Pandas.  

This project uses Django, Pandas, Scikit-learn, and SciPy to create a recommender system for user products.

###### Description
The core of the product which is the recommender system works as described below. The rest of the backend code is normal Django Code including Data Modeling, User Authentication and Creating HTML Layouts

Description:
There are at least three ways we can implement a recommender system.
1. Simply return a list of all products that the user has not tried.

2. Ask the user for a list of products they liked. And based on our knowledge of all products suggest similar products which the user might be interested in. This is the approach many experienced store owners use instinctively since they have broad knowledge about their products. The disadvantage with this is that we require a good amount of knowledge about the particular product before we can make a suggestion

3. The third approach doesn't require us to know anything about the product. We only need to know what other people like or dislike. Then from this information we can easily cluster users according to products they like or dislike. After clustering users with similar preferences we can easily suggest products to a user, which their cluster liked but which the user hasn't tried yet.
