📋 Project Overview
This project performs sentiment analysis on hotel reviews from Tripadvisor to predict customer ratings based on their written reviews. Using Natural Language Processing (NLP) techniques and deep learning models, we analyze customer experiences and classify sentiments as Positive, Negative, or Neutral.

🎯 Key Objectives
Explore hotel review data and customer ratings

Perform feature engineering and text processing

Design and train a deep learning model (BiLSTM) for rating prediction

Evaluate model performance and make predictions

📊 Dataset
The dataset contains 20,000 hotel reviews crawled from Tripadvisor, available from Zenodo.

Columns:

Review: Text of the customer review

Rating: Numerical rating (1-5)

Sentiment_Score: VADER compound sentiment score

Sentiment: Categorical sentiment (Positive/Negative/Neutral)

🛠️ Technologies Used
Python (Pandas, NumPy)

Data Visualization (Matplotlib, Seaborn, Plotly, WordCloud)

NLP Processing (NLTK, VADER Sentiment Analysis, Gensim)

📈 Key Insights
Sentiment Distribution: Most reviews (18,321) are Positive, with 1,093 Negative and 1,077 Neutral

Rating-Sentiment Correlation: Higher ratings (4-5 stars) strongly correlate with positive sentiment

Model Performance: The BiLSTM model achieves accurate sentiment classification and rating prediction

🚀 How to Run
Clone this repository

Install required dependencies:

bash
pip install pandas numpy matplotlib seaborn plotly wordcloud nltk vaderSentiment tensorflow scikit-learn
Download the dataset from the provided link or use the preprocessed version

Open and run the Jupyter notebook: FINAL PROJECT (1).ipynb

📌 Results
Successfully implemented a sentiment analysis pipeline

Built a deep learning model that predicts ratings based on review text

Generated insightful visualizations showing sentiment distribution and patterns

📚 Future Enhancements
Experiment with other deep learning architectures (BERT, Transformer models)

Deploy as a web application for real-time sentiment analysis

Incorporate additional features (reviewer metadata, hotel attributes)

👥 Author
This project was developed as part of a data science portfolio, demonstrating skills in NLP, deep learning, and data analysis.
Deep Learning (TensorFlow/Keras)

Model Evaluation (scikit-learn metrics)
