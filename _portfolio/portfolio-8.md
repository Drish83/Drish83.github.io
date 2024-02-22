---
title: "Property Recommendation"
excerpt: "Given the current property that the user is browsing on the website, in this task, we aim to provide dynamic top k recommendations of ”similar listings” for the user.<br/><img src='/images/property_recommendation.png'>"
collection: portfolio
---

## Objective
Given the current property that the user is browsing on the website, in this task, we aim to provide dynamic top k recommendations of 'similar listings' for the user.
## Accomplishments 
* We use two metrics to compare the quality of recommendations given by different recommenders, Alignment Score and the distance between Recommendation and Original Score. 
* Data preprocessing to encode the oridnal and nonminal features then pass them through StandardScalar.
* Performed recommendation using KNN, KMeans, AGNES and DBScan.  
* We improve the DBScan recommender by using KNN algorithm to find the top k recommendations if the item is identified as an outlier. With this improvement, the
overall alignment score increased to 87.68% and the average distance between recommendations is reduced to 0.307.

## Results
The overall best model we chose to implement the get top recommendations function is the KNN model. It has the highest alignment score of 90.64% and the shortest computation time. 