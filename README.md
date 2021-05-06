# Eluvio-Data-Challenge

## REQUIREMENTS
* pyLDAvis
* plotly.express
* scikit learn
* wordcloud

## PROBLEM DESCRIPTION
This work seeks to do three main things:
* Draw insight from the data as to the user reaction over the years as a measure of the growth of the news channel.
* Visualize the new titles to have a fair idea what the most common topics are about.
* Cluster the titles to draw insight into the main types of news posted and how users react to each of these news types.
* Do a predictive analysis on how different types of news will be reacted to by the readers using the news titles to predict 
the whether or not the news will receive a high number of upvotes.

## Findings 
1. The number of news posts are similar across the different months of the year.
2. The number of news posted has grown steadily over the years and saw a huge spike between middle of 2012 and the first quarter of 2013
3. The news titles most frequently contain the names of countries such as China, India, and Israel.
4. Clustering the news into three main groups, the themes seen are:
  * News surrounding human right issues, politics, and civil unrests.
  * International trade relations and finance.
  * International war and terrorism
5. The number of posts in these different categories is similar over the years
6. News surrounding international war and terrorism are generally upvoted less

## Predicitve Analysis
Two categories were created using a box plot the number of upvotes received for each post. The outliers above the upper fence of 38 were chosen to be the 'high' class
since these news seems as news that receives more reactions than the regular distribution of upvotes.
Different classification algorithms are applied to varying levels of success.
