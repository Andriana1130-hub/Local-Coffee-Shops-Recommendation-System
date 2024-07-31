# Local-Coffee-Shops-Recommendation-System

## Introduction
This project is an interaction Aspect-Based Sentiment Analysis (ABSA) and knowledge-based recommendation system for local coffee shops in Malaysia. It utilizes sentiment analysis, aspect extraction, and large language models (LLMs) to provide personalized recommendations.

## Project Structure
- `coffee_shop_reviews.xlsx`: The dataset containing reviews of local coffee shops.
- `Aspect_based_Sentiment_Analysis.ipynb`: The code for deploying models for sentiment analysis and aspect extraction.
- `LLM_Recommendation_System.ipynb`: The code for interacting with the recommendation system with LLM support.
- `RASA_NLU_QnA.ipynb`: The code for interacting with the recommendation system with RASA NLU support.

## Dataset
The dataset used in this project is coffee_shop_reviews.xlsx, which contains reviews of local coffee shops in Malaysia. It includes various aspects and corresponding sentiments.

## Aspect-Based Sentiment Analysis
The Aspect_based_Sentiment_Analysis.ipynb notebook contains the code for:

## Training models for sentiment analysis.
Extracting aspects from the reviews.
Evaluating the performance of the models.
LLM Recommendation System
The LLM_Recommendation_System.ipynb notebook contains the code for:

## Interacting with the recommendation system using large language models.
Providing personalized recommendations based on user inputs and extracted sentiments.
RASA NLU Interaction
The RASA_NLU_QnA.ipynb notebook contains the code for:

## Interacting with the recommendation system using RASA NLU.
Handling user queries and providing appropriate recommendations.

## Results 
BiLSTM with CBOW perform better compare with others 
Semi-supervised learning (CorEx) perform better than supervised learning (LDA and BERTopic)
LLMs model perform better than RASA NLU model for getting the recommendation 
