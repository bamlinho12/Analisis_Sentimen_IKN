Public Sentiment Analysis on IKN

This project is a simple sentiment analysis to classify public opinion (positive or negative) on the issue of the Capital City of Nusantara (IKN) based on data from social media.

This project was created as part of learning *Natural Language Processing* (NLP) and *Machine Learning*.

## Project Workflow
1.  **Data Collection:** Using a public dataset from Kaggle containing 1,400+ opinions.
2.  **Text Pre-processing:** Cleaning raw text data (case folding, removing punctuation) and applying it to Indonesian root words (Stemming) using Sastrawi.
3.  **Feature Extraction:** Converting the cleaned text into numerical vectors using TF-IDF.
4.  **Model Training:** Training a `Multinomial Naive Bayes` classification model to predict sentiment.
5.  **Evaluation & Visualization:** Evaluating model accuracy and creating a `Word Cloud` to see the most frequently occurring keywords in each sentiment.

## Technologies Used
* Python
* Pandas (For data manipulation)
* NLTK & Sastrawi (For text pre-processing)
* Scikit-learn (For TF-IDF and Naive Bayes model)
* WordCloud & Matplotlib (For visualization)
