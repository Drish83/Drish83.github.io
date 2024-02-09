---
title: "Simplify News"
excerpt: "The project comprises of two main segment, Summarizing News Articles and News4Kids: visualize news.<br/><img src='/images/simplify_news.png'>"
collection: portfolio
---

## Objective
The project comprises of two main segment, Summarizing News Articles and News4Kids: visualize news. 

## Accomplishments 
* Summarizing News Articles: 
    * Data Collection: newspaper library used to obtain articles from BBC and Straits Times. 
    * Data Preprocessing: Many irrelavent html tags are removed and to further refine our dataset we removed stopwords as they add little mening to the content. 
    * Implemented BERT and GPT-2 to provide a summary of the information. 
    * Model evaluation: Each model was evaluated using the ROUGE score, which is a metric that measures the similarity between the generated summary and the reference summary.
* News4Kids
    * Data collection: To collect the articles we scraped the data from Reddit using PRAW which is Python library. 
    * Data preprocessing: we want to avoid content that can be too grotesque and gloomy, therefore we performed sentiment analysis on the extracted content to filter out unwanted content. 
    * Implemented Sentiment analysis using NLTK and TextBlob to choose which one is more suitable for our use case. 
    * Implemented Named Entity Recognition to further refine our output for Stable Diffusion model that will generate comic style images based on the content. 

## Results
TextBlob had a higher accuracy so it was implemented in the final model evaluation. BERT had the highest ROGUE score of 0.99. 
