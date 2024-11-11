# Visualising-Binary-Classifiers
## Visualising Binary Classifiers and Creating Synthetic Datasets
This project is a machine learning task focused on generating and visualising synthetic datasets for binary classification. Here’s a structured summary:

Overview
The project entails creating a series of functions to generate and manipulate synthetic data for machine learning purposes. The data involves two classes: positive (with potential outliers) and negative. The primary functions developed within this framework are:

Generating Positive Data: This function generates data for the positive class, with both inliers and outliers. The data is split across informative and non-informative features, using multivariate normal distributions to simulate a realistic spread. Outliers deviate by having different means and standard deviations.

Generating Negative Data: The negative class data is similar to the positive class but lacks outliers. It also uses informative and non-informative features, created through multivariate normal distributions.

Dataset Creation: This function combines the positive and negative data to form a single dataset, assigning binary labels (0 for negative, 1 for positive). It ensures a randomised order of instances for unbiased training.

Visualisation
Two visualisation functions, plot2d and plot3d, are included to plot the data points in two and three dimensions, respectively. They help visualise class separation and data distribution, aiding in understanding the generated data's structure.

Key Points
Data generation leverages the numpy library.
Visualisation is implemented using matplotlib.
Synthetic datasets follow conventions for machine learning input, with vector-based representation suitable for classification models.
In sum, this project offers a foundational framework for generating and visualising synthetic data, essential for testing classification algorithms.
