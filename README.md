# K-Means Clustering on Iris Dataset with Elbow Method

This project demonstrates how to apply the K-Means clustering algorithm on the Iris dataset from Kaggle, using the Elbow Method to determine the optimal number of clusters. After determining the optimal number of clusters, the model is trained, and predictions are made on the training set.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Results](#results)
- [License](#license)
- [Contact](#contact)

## Overview

In this project, we use K-Means clustering, an unsupervised machine learning algorithm, to classify the Iris dataset into clusters. The Elbow Method is employed to find the optimal number of clusters by plotting the sum of squared distances (inertia) for different values of `k`. This method helps us decide the best number of clusters for the dataset. Once the optimal value of `k` is found, we fit the K-Means model and make predictions on the training data.

## Dataset

The dataset used in this project is the Iris dataset from Kaggle. It consists of 150 samples of iris flowers, with 4 features:
- **Sepal Length**
- **Sepal Width**
- **Petal Length**
- **Petal Width**

The dataset is divided into 3 species:
- Iris Setosa
- Iris Versicolor
- Iris Virginica

Each sample is classified into one of these species based on the 4 features.


## Images:
![Screenshot 2024-11-08 004611](https://github.com/user-attachments/assets/57bfba44-1ca1-46b8-a360-b784e2163c4d)
![Screenshot 2024-11-08 004628](https://github.com/user-attachments/assets/95240db8-cd1a-4192-bfaa-a6838c453c0a)
![Screenshot 2024-11-08 004634](https://github.com/user-attachments/assets/ab20a9c7-9400-4cd6-9dbe-3a6005e197c6)
![Screenshot 2024-11-08 004649](https://github.com/user-attachments/assets/211c66ca-91f2-4bdd-ad45-56f5303bc69e)


## Methodology

1. **Data Preprocessing:**
   - Load the dataset.
   - Split the data into features (X) and labels (y).

2. **Elbow Method:**
   - Apply the Elbow Method to determine the optimal number of clusters (k). This is done by plotting the inertia (sum of squared distances) for different values of `k` and identifying the "elbow" point.

3. **K-Means Clustering:**
   - Apply K-Means clustering using the optimal value of `k`.
   - Fit the model to the data.
   - Predict the cluster labels for the training set.

4. **Results:**
   - Visualize the clusters and centroids.
   - Display the predicted cluster labels for the dataset.

## Installation

To run this project locally, follow the steps below:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/souravdebnath109/Apply-kmeans-algo-and-apply-elbow-method-on-Iris-dataset.git
