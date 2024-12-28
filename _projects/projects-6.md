---
title: "Book Recommender"
excerpt: "A personalized book recommendation system that leverages social media analysis to match users with relevant books."
collection: projects
permalink: /projects/projects-6/
---


## Description
The Book Recommender project aims to create a personalized book recommendation system by analyzing user-generated content on social media, such as tweets, and matching users with books that align with their interests. This project combines natural language processing (NLP), machine learning, and data analysis to deliver targeted recommendations based on user preferences.

### Key Features
- **Social Media Integration**:
  - Analyzes user tweets to identify their interests and preferences.
  - Preprocesses noisy data by removing links, mentions, and emojis for cleaner analysis.
  
- **Book Metadata Completion**:
  - Fills missing book categories using **BERT embeddings** and zero-shot classification, ensuring more accurate recommendations.
  
- **User-Content Classification**:
  - Classifies user-generated posts into predefined book categories using NLP techniques such as **BERT** and **TF-IDF**.
  - Enhances accuracy through cosine similarity to rank book relevance.

- **Recommendation System**:
  - Integrates user preference analysis with book descriptions to provide personalized book suggestions.
  - Generates outputs including categorized user tweets, imputed book metadata, and top book recommendations.

### Results
- Successfully categorized user posts into book genres and recommended books by relevance and alignment with user preferences.
- Enhanced accuracy through advanced classification models and similarity functions, ensuring precise recommendations.
- Created scalable outputs in CSV format for easy accessibility and further analysis.

---

## My Contributions

- **Data Collection and Preprocessing**:
  - Gathered and processed datasets from **Kaggle** and Twitter API.
  - Cleaned noisy tweet data by removing unnecessary elements like links, mentions, and emojis.
  
- **Book Metadata Imputation**:
  - Used **BERT embeddings** and zero-shot classification to fill missing categories for over 1 million books.

- **NLP and Classification**:
  - Implemented **BERT** and TF-IDF-based classification to categorize user tweets into book genres.
  - Applied cosine similarity for ranking recommendations by relevance.

- **Recommendation System Development**:
  - Built a system that combines user preference analysis with book metadata to suggest personalized book recommendations.
  - Ensured seamless integration of classification models with recommendation logic.

- **Team Collaboration**:
  - Collaborated in a team of four to design and implement a scalable solution using **Python**, **tweepy**, **transformers**, and **scikit-learn**.

---

## Tools and Techniques

- **Natural Language Processing**: BERT, TF-IDF, cosine similarity, zero-shot classification.
- **Data Analysis**: Pandas, scikit-learn, Python scripts for preprocessing.
- **APIs**: Twitter API for social media data collection, Kaggle API for book datasets.
- **Machine Learning Models**: BERT embeddings, classification models for user preference analysis.
- **Data Management**: CSV outputs for imputed book categories, categorized tweets, and recommendation results.



For more information, including the repository and implementation details, visit the project on [GitHub](https://github.com/sbaek21/BookRecommender).