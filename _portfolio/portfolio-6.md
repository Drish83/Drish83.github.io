---
title: "Trash Classification with Bayesian Neural Network"
excerpt: "Different combinations of ResNet with Bayesian Neural Network (BNN) are tested for trash classification<br/><img src='/images/trash_classification.png'>"
collection: portfolio
---

## Objective
Different combinations of ResNet with Bayesian Neural Network (BNN) are tested for trash classification

## Accomplishments 
* Dataset collection: we utilised three sources of data: Trashnet dataset, external sources from the web, and non-trash images. This dataset spans six categories and consists of 2527 images in total.
* Model training: We implemented both CNN and BMM transfer learning methods and some variations, so in total we trained 5 models. 


## Results
Densenet121 performed the best in both aspects for the test set while the Densnet121 + BNN performed the best for the valdiation set. As the performance for all 4 transfer learning models are comparable, it suggests that adding BNN to the last 2 layers marginally improves the resnet and densenet model.
