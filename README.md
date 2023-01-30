# Genetic Algorithm for Feature Selection

## Introduction

This project implements a genetic algorithm to determine the most impactful features in a dataset. The objective is to find the optimal subset of features that results in the highest performance of a classifier. The code is written in a Jupyter Notebook file without using any built-in libraries.

## Requirements

To run the code, you will need the following packages installed:
- pandas
- numpy
- scikit-learn

## Methodology

The genetic algorithm is implemented from scratch using the following steps:

1. Initialize a population of random feature subsets.
2. Evaluate the performance of each feature subset using a classifier on the training data and testing data.
3. Select the best feature subsets using a selection operator (e.g. tournament selection).
4. Create new feature subsets using genetic operators such as mutation and crossover.
5. Repeat steps 2-4 for a predetermined number of generations or until a stopping criterion is met (e.g. no improvement in performance).
6. Select the best feature subset from the final generation.
7. Evaluate the performance of the classifier using the selected features on the testing data.
8. Compare the results with the classifier using all the features to show the impact of the feature selection.

## Usage

To run the code, simply open the `feature_selection_ga.ipynb` Jupyter Notebook and run the cells in order.

## Results

The results of the feature selection will be displayed in the Jupyter Notebook. The performance of the classifier is evaluated using accuracy, precision, recall, and F1 score. The results with and without feature selection are compared to show the impact of the feature selection.

## Conclusion

This project demonstrates the implementation of a genetic algorithm for feature selection in a dataset. The results show that the optimal subset of features selected by the genetic algorithm results in better performance compared to using all the features. This technique can be applied to a variety of classification problems to improve the performance of the classifier.
