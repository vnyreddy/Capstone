### Movie recommendation system

by Vinay Reddy Maligireddy

#### Executive summary
The business has an online streaming platform that wants to increase user engagement with the platform and retain user subscriptions. Since there are many streaming platforms in the market, and also within this streaming platform there are thousands of content to choose from, and there is a high chance that users can miss likable content, in another perspective, the business also runs ads between videos and it is important to show more ads to get revenue.

The goal of the business is to create a recommendation system, that can recommend movies to the users that are most likely interested, and help users to find rind right content by recommending, also increasing business revenue.

#### Rationale
There are a lot of streaming platforms out there and these are very competitive, user engagement is the pinnacle to the success of a business. In addition to that, some streaming applications solely depend on Ad revenue, so businesses need to bring more sure engagement. On the other hand, there will be thousands of movies available on stream platforms, and finding the right content also be difficult for the user, and recommending the content that is more likely to interest will retain the user's subscription to the platform.

#### Research Question
Can we accurately recommend movies that can bring more user engagement?

#### Data Sources
The data used to solve this problem is collected from the website called grouplens(https://grouplens.org/datasets/movielens/), GroupLens research has collected movie ratings from the MovieLens website, the data collected thousands of movies from many users in various points of the time. The dataset describes the 5-star ratings and free-text tagging activity from MovieRlens. The users who participated in this survey were selected randomly, and all the selected users had rated at least 20 movies.

Citation: F. Maxwell Harper and Joseph A. Konstan. 2015. The MovieLens Datasets: History and Context. ACM Transactions on Interactive Intelligent Systems (TiiS) 5, 4: 19:1–19:19. https://doi.org/10.1145/2827872

#### Methodology
The methodologies that are used to answer the question are mainly the collobarative recommendation system, and a content based recomendation system, with the help of the different models, which are SVD, SlopeOne, and KNN Basic from the Surprise library. Also, performed content-based recommendations using the TFIDF Vectorizer, and Cosine Similarity from the Sklearn library. Finally, used k-fold cross-validation to compare the performance and accuracy of the models.

#### Results
After the analysis of comparing all the models at this stage, the Singular Value Decomposition(SVD) seems to be the best choice to accurately recommend movies, since it has low mean square error, root mean squared error, and also less fit time.

#### Next steps
The next steps are to improve the model performance and accuracy by hyperparameter tuning with the help of GridSearchCV.

The MovieLens dataset doesn't have explicit tags for each movie, and the dataset is not structured in a way that supports effective content-based recommendation using tags, so need more data collection for tags, and then re-model for effective results.

#### Outline of project

- [Link to notebook 1]()
- [Link to notebook 2]()
- [Link to notebook 3]()


##### Contact and Further Information
