# EECS 731 - Project 3
*Grant Gollier*

## Data

The movie dataset comes from [MovieLens](https://grouplens.org/datasets/movielens/). Due to the dataset's size it is not included in the repository. To test out the notebooks please download the full dataset and extract it into the `large` subfolder in the `data` directory.

## Overview

The goal of the project was to take the aforementioned movie dataset and using clustering to create a recommendation system. I had fairly good success using DBSCAN and K-Means on two differently engineered sets of data and absolutely terrible results using MeanShift. To see the full analysis please see the [1-Clustering Notebook](notebooks/1-Clustering.ipynb).
