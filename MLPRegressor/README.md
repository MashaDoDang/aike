# Humor Score Prediction using Machine Learning

## Project Overview

This project aims to predict humor scores of jokes using machine learning techniques. The application processes joke data from HTML files, encodes the jokes using the SentenceTransformer, and predicts humor scores using a Multi-layer Perceptron Regressor (MLPRegressor). This project demonstrates the integration of various machine learning libraries and tools to achieve the desired functionality. 

## Features

- **Data Extraction**: Extracts jokes from HTML files using BeautifulSoup.
- **Data Storage**: Stores joke data and ratings in a SQLite database.
- **Data Preprocessing**: Handles missing values, scales data, and splits it into training and validation sets.
- **Model Training**: Trains multiple configurations of MLPRegressor to find the best model.
- **Prediction**: Uses the trained model to predict humor scores of new jokes.
- **Visualization**: Plots training and validation loss over epochs to monitor the model's performance.

## Skills Gained

- **HTML Parsing**: Learned to parse and extract specific content from HTML files using BeautifulSoup.
- **Database Management**: Gained experience in creating and managing SQLite databases.
- **Data Preprocessing**: Applied data preprocessing techniques such as handling missing values, scaling features, and splitting datasets.
- **Machine Learning**: Trained and evaluated machine learning models using Scikit-Learn's MLPRegressor.
- **Sentence Embedding**: Utilized the SentenceTransformer model to convert textual data into numerical embeddings.
- **Data Visualization**: Created plots using Matplotlib to visualize model performance metrics.
- **Model Evaluation**: Assessed model performance using mean squared error (MSE) and visualized training and validation loss.
