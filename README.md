This project focuses on stress detection from social media text using machine learning techniques. The model is developed using the Dreaddit dataset, which contains Reddit posts labeled as stressed (1) or non-stressed (0). The dataset reflects real-world user-generated content, making it suitable for analyzing mental health patterns.

The project follows a complete data science pipeline, starting with data cleaning and preprocessing. Missing values and duplicate records are removed, and text data is standardized by converting it to lowercase. A new feature, text length, is also created to capture basic structural information from the posts.

For feature extraction, TF-IDF (Term Frequency–Inverse Document Frequency) is used to convert textual data into numerical form. This allows machine learning models to process and analyze the text effectively. The dataset is then split into training and testing sets using an 80:20 ratio.

A Logistic Regression model is applied for classification, as the problem involves predicting binary outcomes (stress vs non-stress). The model is trained on the processed data and evaluated using metrics such as accuracy score, confusion matrix, and classification report.

In addition, Exploratory Data Analysis (EDA) is performed using matplotlib. Visualizations such as bar charts, pie charts, histograms, scatter plots, heatmaps, and box plots are used to understand data distribution, feature relationships, and patterns in stress levels.

This project demonstrates that simple and interpretable machine learning techniques can effectively solve real-world problems related to mental health analysis. It is designed to be beginner-friendly while still covering important concepts such as data preprocessing, NLP, and model evaluation.

Tech Stack:-
Python 🐍
Pandas & NumPy
Matplotlib 📊
Scikit-learn 🤖
