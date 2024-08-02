# Movie-Genre-Prediction

Project Overview:
This project focuses on building a Movie Genre Classification model using machine learning techniques. The workflow includes data cleaning, visualization, preprocessing, and model creation to predict movie genres based on plot summaries.

Steps:

Data Cleaning 🧹

Renamed and merged columns from 'movie_metadata' and 'plot_summary' dataframes.
Cleaned the 'genre' column and removed rows with missing genre tags.
Data Visualization 📊

Visualized the distribution of different movie genres.
Data Preprocessing 🛠️

Cleaned plot summaries, removed stopwords, and applied stemming.
Encoded genres into target variables using MultiLabelBinarizer.
Split the dataset into training and test sets.
Extracted features from the text corpus using TfidfVectorizer.
Model Creation 🤖

Developed a logistic regression model to classify movie genres.
Tech Stack:

Languages: Python
Libraries: Pandas, NLTK, scikit-learn
Techniques: Data Cleaning, Text Preprocessing, Logistic Regression, TfidfVectorizer, MultiLabelBinarizer
Feel free to explore the code and contribute! 💻🔍

