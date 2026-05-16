# SENTIMENT-ANALYSIS

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SAIRAJ JANARDAN PATIL

*INTERN ID*: CTIS8472

*DOMAIN*: DATA ANALYTICS 

*DURATION*: 6 WEEKS

*MENTOR*:  NEELA SANTHOSH KUMAR

*DESCRIPTION*: Of Project Sentiment Analysis

This project focuses on performing sentiment analysis on textual social media data using Machine Learning and Natural Language Processing (NLP) techniques. The main objective of the project is to classify text into different sentiment categories such as positive, negative, or neutral and derive meaningful insights from user-generated content. Sentiment analysis is widely used in social media analytics, customer feedback systems, product reviews, and opinion mining to understand public emotions and reactions toward products, services, events, or brands.

The project begins with importing essential Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn. The dataset used for the analysis contains textual data along with sentiment labels and additional attributes such as date and platform information. The dataset is loaded using Pandas and explored to understand its structure and contents.

Before training the machine learning model, text preprocessing is performed to clean and standardize the textual data. A custom text cleaning function is implemented using regular expressions. The preprocessing steps include converting text to lowercase, removing URLs, removing user mentions, and eliminating special characters and unwanted symbols. These preprocessing operations help improve the quality of the text data and enhance the performance of the sentiment classification model.

After preprocessing, the cleaned text is transformed into numerical format using the TF-IDF (Term Frequency–Inverse Document Frequency) vectorization technique. TF-IDF converts textual data into feature vectors by measuring the importance of words within the dataset. The vectorized data is then divided into training and testing datasets using the train-test split method to evaluate the model effectively.

A Logistic Regression model is used for sentiment classification. Logistic Regression is a popular supervised machine learning algorithm widely used for text classification tasks because of its simplicity, efficiency, and strong performance on high-dimensional text data. The model is trained on the training dataset and then used to predict sentiments for the testing dataset.

The project evaluates model performance using several metrics such as accuracy score, classification report, and confusion matrix. The classification report provides detailed evaluation metrics including precision, recall, and F1-score, while the confusion matrix visually represents the prediction performance of the model. Data visualization techniques using Matplotlib and Seaborn are also applied to better understand sentiment distribution and model outcomes.

In addition to sentiment classification, the project performs trend analysis over time by converting separate year, month, and day columns into a unified date format. Sentiment trends are analyzed to observe how public opinion changes over time. Platform-wise sentiment analysis is also conducted to compare sentiment distributions across different social media platforms.

Furthermore, the project identifies the most influential positive and negative words based on the trained Logistic Regression model coefficients. By analyzing these top contributing words, it becomes possible to understand which terms strongly influence positive or negative sentiment predictions.

This project demonstrates the practical implementation of sentiment analysis using Machine Learning, Natural Language Processing, and data visualization techniques. It highlights how textual social media data can be processed, analyzed, and interpreted to extract valuable insights regarding user opinions and emotional trends.

Overall, the project provides a complete workflow for sentiment analysis, including data preprocessing, feature extraction, machine learning model training, evaluation, visualization, and insight generation, making it an effective example of applied NLP and social media analytics.
