K-Means Clustering From Scratch

This repository contains code for implementing a K-Means clustering algorithm from scratch in Python and comparing it to the scikit-learn implementation.

Project Overview

Build a K-Means clustering algorithm from scratch using Python and Pandas.
Compare the custom implementation to the reference implementation from scikit-learn.
Project Steps

Pseudocode: Develop pseudocode for the K-Means algorithm.
Implementation: Code the K-Means algorithm in Python.
Visualization: Plot the identified clusters using the custom algorithm.
Comparison: Compare the performance of the custom algorithm to scikit-learn's K-Means implementation.
K-Means Clustering Overview

K-Means is an unsupervised machine learning technique used to group data points into clusters based on their similarities. It helps uncover patterns in unlabeled data, enabling more effective data analysis.

K-Means Algorithm

Specify k: Define the desired number of clusters (k).
Centroid Initialization: Randomly initialize a centroid (center point) for each cluster.
Cluster Assignment: Assign each data point to the closest centroid based on distance (usually Euclidean distance).
Centroid Update: Recalculate the centroid of each cluster as the geometric mean of the data points assigned to it.
Repeat Steps 3 & 4: Repeat steps 3 and 4 until the centroids no longer change significantly. Each repetition is called an iteration.
Code

The code for this project is located in the clustering.ipynb Jupyter Notebook file.

Local Setup

Installation

Ensure you have the following installed locally:

Python (version 3.8 or higher)
Python packages:
pandas
numpy
scikit-learn
Data

The specific file used is male_players24.csv.
