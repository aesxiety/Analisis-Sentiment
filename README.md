# Sentiment Analysis of Indonesian National Team's World Cup Qualification Matches on Instagram Using Support Vector Machine (SVM)

## Authors: 
- Muchlas Andrey Pahlevi
- Dwi Reza Ariyadi

## Overview:
This study analyzes public sentiment toward the Indonesian national football team's performance in World Cup qualifiers, using Instagram comments as the dataset. The analysis is performed using the **Support Vector Machine (SVM)** algorithm, which classifies sentiments into three categories: positive, neutral, and negative.

## Dataset:
The dataset consists of 7,257 raw comments from the official Instagram account of the Indonesian national football team. After preprocessing steps like **cleaning text**, **case folding**, **tokenization**, and **stopword removal**, 6,731 comments were used for modeling.

## Methodology:
1. **Data Preprocessing**: Text comments were transformed using **TF-IDF** (Term Frequency-Inverse Document Frequency) to assign weights to the words.
2. **Sentiment Classification**: The SVM model with a linear kernel was used to classify the sentiments.
3. **Evaluation Metrics**: The model's performance was measured using accuracy, precision, recall, and F1-score.

## Results:
- **Accuracy**: 79%
- **Precision**: 77% for negative, 79% for neutral, 80% for positive sentiments.
- **Recall**: The model had the highest recall of 93% for neutral sentiment.
- **F1-score**: Best F1-score of 0.86 for neutral sentiment.

## Conclusion:
The SVM model effectively classified the sentiment from public Instagram comments, providing a comprehensive view of public perception towards the Indonesian national team's performance. The results can help stakeholders in formulating communication strategies on social media.

## Keywords:
- Sentiment Analysis
- Indonesian National Team
- World Cup Qualifiers
- Support Vector Machine (SVM)
- Instagram
