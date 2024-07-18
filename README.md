<h1 align="center">
  🏨 NLP with Hotel Review 
</h1>

<p align="center">
  <img src="https://github.com/aidos-askhatuly/Hotel-Review-Sentiment-Analysis/blob/main/pic/1_75QIGkBYRF6LgAeuzKKyNw.webp" alt="Description" width="600" height="400">
</p>

## 🎯 Project Overview
This project aims to help Hotel Management Inc. gain deeper insights into the factors that contribute to customer satisfaction and higher ratings in hotel stays, as well as identify areas for improvement. By analyzing a large dataset of hotel reviews and stay details using Natural Language Processing techniques, we seek to uncover patterns and trends that can inform strategic decisions and service enhancements.

**Key Objectives:**

1. Identify the main attributes of hotel stays that correlate with positive customer sentiment
2. Analyze negative reviews to pinpoint specific hotel services that are not well-perceived by visitors
3. Examine the impact of various factors (average score, location, length of stay, etc.) on reviewer scores
4. Develop a predictive model to classify review sentiment based on textual and numerical features
5. Provide actionable insights to hotel management for enhancing guest experiences and addressing pain points

##  📊 Dataset
The analysis is based on a comprehensive dataset containing:
* Text fields for positive and negative feedback
* Details about each stay (hotel location, duration, etc.)
* Target variable: Reviewer_Score (1 for positive sentiment, 0 for negative)

## 🛠️ [Project Workflow](https://github.com/aidos-askhatuly/Hotel-Review-Sentiment-Analysis/blob/main/Hotel_Reviews.ipynb)
1. Data Preprocessing
* Text cleaning and normalization
* Feature engineering from stay details
* Handling missing, null, and duplicate values

2. Exploratory Data Analysis
* Identify common themes in positive and negative reviews
* Analyze the distribution of scores across different stay attributes
* Deep dive into negative reviews to categorize and quantify common complaints

3. Natural Language Processing
* Implement Bag of Words technique to convert text data into numerical features
* Topic modeling to extract key themes from both positive and negative reviews
* Sentiment analysis to gauge the intensity of positive and negative feedback

4. Machine Learning
* Develop classification models using Bag of Words features to predict review sentiment
* Evaluate model performance using metrics like accuracy and ROC-AUC

5. Feature Importance Analysis
* Identify the most influential words and phrases in determining positive and negative reviews
* Highlight key drivers of negative sentiment

6. Insights Generation
* Synthesize findings into actionable recommendations for hotel management

## 🔍 Findings and Conclusions
Our sentiment analysis model for hotel reviews achieved:
* Model Accuracy: 78.8%
* AUC Score: 86.7%, indicating strong discrimination between positive and negative reviews

**Key Findings:**
* The model effectively identifies positive sentiment, providing reliable insights for management decisions.
* Top 20 positive words were identified, offering trustworthy indicators of guest satisfaction.
* Top 20 negative words were identified, offering trustworthy indicators of guest complaints.
* N-grams and stemming improved the identification of meaningful multi-word indicators.
* Average Score emerged as the most reliable predictor of review sentiment.

**Recommendations:**
* Focus on improving the Average Score metric as a key performance indicator.
* Conduct targeted analysis of lower-scored reviews to identify areas for improvement.
* Utilize the identified positive words and phrases to reinforce successful aspects of guest experiences.
* Utilize the identified negative words and phrases to improve guest experiences.
* Consider more advanced vectorization techniques for potentially improved results.

This project demonstrates the power of NLP in extracting actionable insights from hotel reviews, providing Hotel Management Inc. with data-driven strategies to enhance guest satisfaction and address pain points effectively.
