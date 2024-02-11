# Clustering Analysis

## Overview

This Python script performs clustering analysis on a dataset using various clustering algorithms and preprocessing techniques.
The notebook includes the following steps:
1. Loading the dataset
2. Using pycaret to perform various clustering methods
3. Printing the results

The following clustering methods are used:
1. K-Means Clustering
2. Hierarchical Clustering
3. Birch Clustering

## Dependencies
1. Jupyter Notebook
2. pandas
3. numpy
4. pycaret
5. sklearn.metrics

You can install the required dependencies using pip:
pip install jupyter pandas sklearn.metrics numpy pycaret

## Notebook Information

This notebook was originally created in Google Colab. You can access the original notebook [here](https://colab.research.google.com/drive/15gpAww3HiQ3kRRLWp5qcxjKl4HOrqZ9h).

## Usage

1. Clone this repository to your local machine.
2. Open the script Clustering.ipynb in a Jupyter Notebook environment or any other compatible environment.
3. Run each cell in the notebook sequentially to perform clustering analysis on your dataset.

## Dataset

The script expects a CSV file named Raisin_Dataset.csv containing the data to be clustered. Make sure to update the file path if your dataset is located elsewhere.

## Result

The script generates results for three clustering algorithms: K-Means Clustering, Hierarchical Clustering, and Birch Clustering. The results include evaluation metrics such as Silhouette Score, Calinski-Harabasz Score, and Davies-Bouldin Score for different clustering configurations and preprocessing techniques.

## K-Means Clustering

The results for K-Means Clustering are stored in the DataFrame result1df.

## Hierarchical Clustering

The results for Hierarchical Clustering are stored in the DataFrame result2df.

## Birch Clustering

The results for Birch Clustering are stored in the DataFrame result3df.

##License

This script is provided under the MIT License.


Make sure to replace the placeholders such as file paths, dataset names, and other specific details with the correct information from your script. This README file will help users understand how to use your script and interpret the results it generates.

