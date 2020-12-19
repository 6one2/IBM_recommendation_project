# __Recommendations for IBM Watson Studio platform__

## __Introduction__

As part of the [Udacity Data Science nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025), this project analyses the interactions that users have with articles on the [IBM Watson Studio platform](https://www.ibm.com/cloud/watson-studio?p1=Search&p4=43700050290119151&p5=e&cm_mmc=Search_Google-_-1S_1S-_-WW_NA-_-ibm%20watson%20studio_e&cm_mmca7=71700000061102158&cm_mmca8=kwd-432445750759&cm_mmca9=Cj0KCQiAw_H-BRD-ARIsALQE_2MoTEK0V4LsXQtIJ8a2xt9RhB3heipFM92DqudOlgfZWbx7DixlskoaAg9TEALw_wcB&cm_mmca10=405936285044&cm_mmca11=e&gclid=Cj0KCQiAw_H-BRD-ARIsALQE_2MoTEK0V4LsXQtIJ8a2xt9RhB3heipFM92DqudOlgfZWbx7DixlskoaAg9TEALw_wcB&gclsrc=aw.ds), and make recommendations to them about new articles you think they would interact with.

## __Data exploration__

Basic exploration of number users, number of articles, and number of interactions per articles...

## __Rank Based Recommendations__

First find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users.

## __User-User Based Collaborative Filtering__

In order to build better recommendations for the users of IBM's platform, we look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users.

## __Content Based Recommendations (NOT IMPLEMENTED)__

## __Matrix Factorization__

Finally, we completed a machine learning approach to building recommendations. Using the user-item interactions, we build out a matrix decomposition. Using your decomposition, we assessed how well we can predict new articles an individual might interact with. This basic recommendation system is discussed in the last section of the notebook.