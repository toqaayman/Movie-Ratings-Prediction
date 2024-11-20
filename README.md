# Movie Ratings Prediction Using K-Nearest Neighbors

## Overview
This project utilizes the K-Nearest Neighbors (KNN) algorithm to predict movie ratings based on movie attributes such as vote count, release year, and genre. The goal is to apply machine learning techniques to understand how different features influence movie ratings.

## Data Description
The project uses a dataset that includes several attributes of movies, which are preprocessed and used as inputs for the KNN model:
- **vote_count**: The number of votes the movie received.
- **release_year**: The year the movie was released.
- **genres**: The movie's genres, processed into numerical values.

## Features
Feature engineering plays a crucial role in preparing the dataset for modeling:
- Numerical encoding of genres.
- Extraction and conversion of the release year from the release date.
- Selection of movies based on a vote average of 6 or higher and a release date post-1970.

## Prerequisites
The following Python libraries are required to run the project:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```
## Usage
1. Clone the repository.
2. Install the required dependencies.
3. Run the Jupyter notebook to train the model and make predictions.
## Model Training and Evaluation
The KNN algorithm was applied in two forms: as a regressor and a classifier.
Model performance was assessed using metrics such as Mean Squared Error for regression and accuracy for classification.
## Results
Visualizations were created to analyze the distribution of average ratings and the effectiveness of the predictive models. The models showed promising results in predicting the movie ratings based on historical data.

## Contributing
Feel free to fork the project, make changes, and submit a pull request if you have improvements or new features you would like to add.
