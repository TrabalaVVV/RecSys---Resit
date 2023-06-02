# RecSys---Resit
Below you can find all the code that I used to program a recommender system on a known dataset by Yelp. The dataset includes a large sample of user reviews for businesses located in the US, including a vast array of qualitative(star reviews, number/ relevance of reviews) and quantitative(full text of reviews) features about users.
We were tasked to perform collaborative filtering based on KNN and SVD. For KNN I made it by hand by encoding the string-based IDs into integers, splitting the sets of indices to create testing, training and validating datasets and finally caluclated the cosine-distance similarities. Then based on these distances I am able to "recommend" potentially viable items (businesses) to a selected user.
For SVD I used the Surprise package and documented my approach while reffering to the documentation page. This assignment is a part of the System Development for Marketing module held by the University of Applied Sciences in Amsterdam
