# Sentiment-and-Emotion-Analysis-of-Airline-Tweets
**Problem Statement**:  
Analyze airline customer tweets to determine the overall sentiment and emotional tone.

**Data**:  
- Source: Airline Twitter Sentiment dataset (`Tweets.csv`)
- Description: Customer tweets labeled with positive, neutral, or negative sentiment.

**Data Mining Operations**:  
- Data wrangling: Cleaned text data (removed mentions, URLs, punctuation).
- Modeling: Applied VADER SentimentIntensityAnalyzer for sentiment classification. Used NRCLex for emotion tagging.
- Libraries: `nltk`, `matplotlib`, `wordcloud`, `nrclex`
- Reason for model choice: VADER is optimized for social media sentiment; NRCLex provides rich emotion detection.

**Model Outputs**:  
- Word Cloud highlighting frequent terms.
- Sentiment Distribution bar chart.
- Emotion Distribution bar chart (fear, sadness, anger, joy, surprise).

**Limitations**:  
- Sarcasm and mixed emotions in tweets can lead to misclassification.
- NRCLex detects a wide range of emotions that had to be filtered for analysis.

**Were you able to effectively solve the problem?**  
Yes, sentiment and emotion patterns were effectively extracted, providing insights into airline customer experiences.
