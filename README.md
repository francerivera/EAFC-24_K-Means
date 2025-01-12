# K-Means Clustering Algorithm from Scratch

## Project Overview

Welcome to the K-Means Clustering project! In this project, we'll build a k-means clustering algorithm from scratch. Clustering is a fantastic way to find hidden patterns in your data, and k-means is one of the most popular methods for achieving this.

We'll implement our algorithm using Python and pandas, and then compare it to the scikit-learn implementation.

## Project Steps

1. Write pseudocode for the algorithm
2. Implement the k-means algorithm
3. Visualize the clusters produced by our algorithm
4. Compare the performance with scikit-learn's implementation

## K-Means Overview

K-means clustering is an unsupervised machine learning technique that helps in grouping similar data points. It works through the following iterative process:

1. Choose the number of clusters (k).
2. Randomly initialize the centroids for each cluster.
3. Assign data points to the nearest centroid.
4. Update the centroids based on the mean of the assigned data points.
5. Repeat steps 3 and 4 until the centroids stabilize.

## Code Structure

The code for this project is available in the `cluster.ipynb` notebook.

### File Details

- `cluster.ipynb` - Contains the full implementation of the k-means clustering algorithm.

## Local Setup

### Installation

To run this project, you'll need:

- Python 3.8 or higher
- The following Python packages:
  - `pandas`
  - `numpy`
  - `scikit-learn`


## Data

We'll be using data from FIFA, which you can download [here](https://www.kaggle.com/datasets/stefanoleone992/ea-sports-fc-24-complete-player-dataset?select=male_players.csv). The specific file used is male_players.csv. I just rename it to male_players24.csv to be specific
