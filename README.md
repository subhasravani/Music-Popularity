# Music Popularity Prediction

This project aims to predict the popularity of songs based on their audio features using machine learning.

## Dataset

The project uses the "music.csv" dataset, which contains various audio features of songs and their corresponding popularity scores.

## Project Workflow

1. **Data Loading:** Loads the music dataset into a Pandas DataFrame.
2. **Data Exploration:** Analyzes the distribution of features, identifies missing values, and examines relationships between variables.
3. **Data Cleaning:** Handles missing values and removes duplicate entries.
4. **Feature Engineering:** Creates new features from existing data, such as song title length and interaction terms.
5. **Data Splitting:** Divides the data into training, validation, and testing sets.
6. **Model Training:** Trains regression models, including Linear Regression, Random Forest, and Gradient Boosting.
7. **Model Optimization:** Tunes hyperparameters of the models using GridSearchCV.
8. **Model Evaluation:** Evaluates the best model's performance on the test set using metrics like MAE, RMSE, and R-squared.

## Results

The Random Forest model achieved the best performance with an MAE of 9.97 on the validation set and 15.89 on the test set.

## Insights and Next Steps

* Explore additional features or feature transformations to improve model performance.
* Investigate different model architectures or ensemble methods.

## Usage

1. Upload the "music.csv" dataset to your Colab environment.
2. Run the notebook cells sequentially to execute the project workflow.

## Dependencies

* Python 3.x
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn
