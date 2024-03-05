# Steam Reviews Analysis

This project is part of the Data Science course MADS-SMA (Social Media Analytics).

### Description
The goal of this project is to perform comprehensive sentiment analysis and text classification on Steam game reviews to gain valuable insights into user sentiments and preferences. By leveraging natural language processing (NLP) techniques, the project aims to achieve the following objectives:

__Sentiment Analysis__: Analyze the sentiment expressed in Steam game reviews using both rule-based methods (VADER sentiment analysis) and machine learning models.

__Text Classification__: Build and evaluate a text classification model to categorize reviews into positive and negative sentiments based on user votes (upvotes or downvotes).

__User Behavior Exploration__: Utilize additional information such as playtime, number of games owned, and number of reviews written by users.

By achieving these objectives, the project aims to provide game developers, platform administrators, and gamers with actionable insights to enhance user experiences, understand popular game trends, and potentially improve game recommendations on the Steam platform.

### Libraries Used:

1. **BeautifulSoup**: Used for web scraping of Steam database.
2. **NLTK: Natural Language Toolkit**: Used for symbolic and statistical processing of natural language.
3. **Pandas**: For data manipulation and analysis.
4. **Scikit-Learn (sklearn)**: Utilized for machine learning tasks such as model selection, hyperparameter tuning, and evaluation.

**Skills and Techniques**:

1. **Data Collection**: Fetched Steam game reviews using the Steam API, focusing on popular games. Extracted relevant information such as reviews, votes, playtime, and user details.
2. **Data Preprocessing**: Cleaned and organized the data for analysis. Obtained a DataFrame with columns including review text, user details, voting information, and more.
3. **Sentiment Analysis**: Applied sentiment analysis using NLTK's SentimentIntensityAnalyzer. Achieved an accuracy of approximately 82%, classifying reviews into positive or negative sentiments.
4. **Text Classification (Naive Bayes)**: Performed text classification using a Naive Bayes classifier. Achieved an accuracy of 80%, with high precision, recall, and F1-score for positive sentiments.

 ### Conclusion:

__Sentiment Analysis Insights__:

- The sentiment analysis results provide a quick overview of the overall sentiments expressed in the reviews.
- A moderate accuracy of 82% indicates reasonable success in classifying positive and negative sentiments.

__Text Classification Insights__:

- The Naive Bayes classifier excelled in accurately predicting positive sentiments, achieving an accuracy of 80%.
- Precision, recall, and F1-score metrics indicate robust performance, particularly for the positive sentiment class.

__Considerations and Next Steps__:

- The project offers valuable insights into the sentiments associated with popular Steam games.
- Future enhancements could include exploring more sophisticated sentiment analysis models and classifiers, especially for larger datasets.
- Additionally, the project can be extended to include more advanced natural language processing (NLP) techniques, such as topic modeling or deep learning models, for deeper insights.

__Application__:

- The sentiment analysis and text classification models can be utilized to automatically categorize and understand user sentiments in Steam game reviews.
- Developers and stakeholders can use these insights to gauge user satisfaction, identify areas for improvement, and make informed decisions about game development and marketing strategies.

In conclusion, the project successfully leverages sentiment analysis and text classification to gain valuable insights into user sentiments in Steam game reviews. The high accuracy achieved by the Naive Bayes classifier demonstrates the effectiveness of the approach. This analysis can be a valuable tool for game developers and the gaming community to better understand player experiences and preferences.
