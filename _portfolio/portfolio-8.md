---
title: "Property Recommendation"
excerpt: "Given the current property that the user is browsing on the website, in this task, we aim to provide dynamic top k recommendations of ”similar listings” for the user.<br/><img src='/images/food_classification_2.png'>"
collection: portfolio
---`

## Objective
Given the current property that the user is browsing on the website, in this task, we aim to provide dynamic top k recommendations of ”similar listings” for the user.
## Accomplishments 
* Dataset collection: we utilised data scrapers to crawl images from various sources and saved the images, path and category to a csv file. 
* EDA: We went thrrought multiple checks to clean our dataset, by removing duplicates, removing images with multiple food items and many more to get a clean dataset. 
* Data Augmentation and Preprocessing: Resize, Normalization, Color Saturation, Random flip were some techniques we used to increase our dataset and improve the quality of it. 
* Model Training: We implemented MLP as our baseline model initially, then implement CNN. 
* Model Improvement: Since both the models did not perform very well, we introduction batch normalization for MLP and ResNet instead. 

## Results
ResNet with transfer learning(from ImageNet weights) had the highest accuracy of 0.77. 