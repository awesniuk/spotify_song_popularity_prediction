# Spotify Charts Analysis

This project analyzes Spotify chart data to understand trends and patterns in music popularity.

Source dataset: https://www.kaggle.com/datasets/dhruvildave/spotify-charts

## Data

The dataset used for this analysis contains information about songs that appeared on Spotify's "Top 200" and "Viral 50" charts. It includes features such as song rank, streams, popularity, artist, album, audio features (danceability, energy, etc.), and available markets.

## Analysis

The project performs the following analysis steps:

**1. Data Cleaning and Preprocessing:**
   - Handling missing values
   - Converting data types
   - Encoding categorical variables
   - Scaling numerical features

**2. Exploratory Data Analysis (EDA):**
   - Visualizing data distributions (histograms, scatter plots)
   - Identifying correlations between features (heatmap)
   - Analyzing song life cycles and trends

**3. Feature Engineering:**
   - Creating new features like "days_on_chart" and "num_of_available_markets"

**4. Modeling:**
   - Building a Random Forest Regressor to predict song popularity
   - Tuning hyperparameters using GridSearchCV
   - Evaluating model performance using metrics like MSE, RMSE, MAE, and R^2

## Results

The analysis reveals insights into the factors that contribute to song popularity on Spotify, such as audio features, artist popularity, and chart performance. The Random Forest model achieves good accuracy in predicting song popularity based on the available features.

## Usage

To run this project, you will need the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- plotly
- scikit-learn

You can run the code in a Jupyter Notebook or Google Colab environment. The code is well-documented and includes explanations for each step of the analysis.

## Future Work

Possible extensions of this project include:

- Exploring different machine learning models for popularity prediction
- Incorporating external data sources like social media trends
- Building a web application to visualize and interact with the analysis results
