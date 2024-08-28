---
title: "Logo Detection in Images and Videos"
excerpt: "Service to detect brand logos from an unknown dataset of images and videos..<br/><img src='/images/logo.jpg'>"
collection: portfolio
---

## Objective
Service to detect brand logos from an unknown dataset of images and videos.

## Accomplishments 
* Compiled a diverse training dataset using both public and internal data sources.
* Converted the labeling to a binary classification: 'Has Logo' or 'No Logo'.
* Trained a YOLOv7 model on over 40,000 images.
* Evaluated model performance using the mean Average Precision (mAP) metric; however, initial results showed that detected logos had low confidence scores.
*  Addressed the high number of false positives by integrating a template matching process using Canny edge detection to dynamically adjust the threshold and match the detected logos with brand logo templates provided.
 * This process significantly reduced false positives by refining the final set of detected logos.

## Results
Despite the low confidence scores in detections, the overall pipeline achieved a high accuracy rate of 93% in detecting logos from an unseen dataset.