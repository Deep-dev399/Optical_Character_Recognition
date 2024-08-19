# Optical_Character_Recognition
# Handwritten-Digit-Recognition-Centroids
This Python script demonstrates the process of training a classifier to recognize handwritten digits using the MNIST dataset. The script utilizes centroid-based feature extraction, splits the data into training and testing sets, employs a classifier, and evaluates its accuracy.

# Steps:

## Load MNIST Dataset:

Fetches the MNIST dataset containing handwritten digit images along with their corresponding labels.

## Variable Number of Blocks:

Divides each image into a variable number of blocks (e.g., 9 blocks). This partitioning allows for more granular feature extraction.

## Centroid Feature Extraction:

Calculates the centroid of each block within the image.
Uses the centroid coordinates as features for training the classifier.
Performs centroid calculation without using built-in functions, implementing custom logic.

## Split Data into Train and Test Sets:

Divides the dataset into training and testing sets, typically following a split ratio such as 70-30%.

## Choose Classifier:

Selects a classifier from built-in options, such as Support Vector Machine (SVM), Random Forest, or k-Nearest Neighbors (k-NN).
Train Classifier:

Trains the chosen classifier using the centroid features extracted from the training set.

## Evaluate Accuracy:

Tests the trained classifier on the testing set to evaluate its accuracy.
Calculates the accuracy metric, which represents the percentage of correctly classified digits.

