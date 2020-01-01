# Exoplanet Exploration

![exoplanets.jpg](images/exoplanets.jpg)

## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

To help process this data, we will create machine learning models capable of classifying candidate exoplanets from the raw dataset.

In this project, we will need to:

1. [Preprocess the raw data](#Preprocessing)
2. [Tune the models](#Tune-Model-Parameters)
3. [Compare two or more models](#Evaluate-Model-Performance)

### Pair Plot
![Pair Plot](images/pairplot.png)

- - -

## Instructions

### Preprocess the Data

* Preprocess the raw dataset prior to fitting the model.
* Perform feature selection and remove unnecessary features.
* Use `MinMaxScaler` to scale the numerical data.
* Separate the data into training and testing data.

### Tune Model Parameters

* Use `GridSearch` to tune model parameters.
* Tune and compare at least two different classifiers.

### Evaluate Model Performance

Compare the performance of two or more classifiers to determine the best model performance.

1. Decision Tree
2. K Nearest Neighbors
3. Logistic Regression
4. Support Vector Machine

### Compare Results

- Decision Tree: Accuracy Rate = 81%
- K Nearest Neighbors (KNN): Accuracy Rate = 75%
- Logistic Regression: Accuracy Rate = 52%
- Support Vector Machine (SVM): Accuracy Rate = 62%

- - -

## Resources

* [Exoplanet Data Source](https://www.kaggle.com/nasa/kepler-exoplanet-search-results)
* [Scikit-Learn Tutorial Part 1](https://www.youtube.com/watch?v=4PXAztQtoTg)
* [Scikit-Learn Tutorial Part 2](https://www.youtube.com/watch?v=gK43gtGh49o&t=5858s)
* [Grid Search](https://scikit-learn.org/stable/modules/grid_search.html)

- - -

## Notes

* Start by cleaning the data, removing unnecessary columns, and scaling the data.
* Try a simple model first, and then tune the model using `GridSearch`.

## Acknowledgements

* This dataset was published as-is by NASA. 
