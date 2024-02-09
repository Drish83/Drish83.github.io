---
title: "Singaporean Food Image Classification"
excerpt: "Apply deep learning techniques to build a food imagerecognition technology that is developed to recognize more than 10 Singaporean foods<br/><img src='/images/food_classification_2.png'>"
collection: portfolio
---`

## Objective
Build a food image recognition technology to recognize more than 10 Singaporean food. Model can then be reused to develop a food recommendation website or app based on the image uploaded by the users.
## Accomplishments 
* Dataset collection: we utilised data scrapers to crawl images from various sources and saved the images, path and category to a csv file. 
* EDA: We went thrrought multiple checks to clean our dataset, by removing duplicates, removing images with multiple food items and many more to get a clean dataset. 
* Data Augmentation and Preprocessing: Resize, Normalization, Color Saturation, Random flip were some techniques we used to increase our dataset and improve the quality of it. 
* Model Training: We implemented MLP as our baseline model initially, then implement CNN. 
* Model Improvement: Since both the models did not perform very well, we introduction batch normalization for MLP and ResNet instead. 

## Results
ResNet with transfer learning(from ImageNet weights) had the highest accuracy of 0.77. 