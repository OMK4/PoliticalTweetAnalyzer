# PoliticalTweetAnalyzer
Using Pandas and ScikitLearn API on Tweets Grabbed Through Twitter API

Cluster Users Based on Hashtags

1/Pre-Process
- Keep Users and Hashtags that are actively used. (threshold: 20)
- Remove Retweets

2/Clustering
- Run K-Means Algorithm
- Run Agglomerative Hierarchical Clustering Algorithm

3/Compare Results
- Compare K-Means and Agglomerative Hierarchical Clustering
- Use Ground Truths to compare SSE-based and MAX-based erroring
