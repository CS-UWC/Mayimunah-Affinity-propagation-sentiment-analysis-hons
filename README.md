9-# AffinityP-Sentiment-Analysis

# Sentiment Analysis using Affinity Propagation Clustering

## Introduction
This project uses Affinity Propagation clustering to perform sentiment analysis on a dataset of twitter(X) texts. The goal is to group similar tweets together based on their sentiment.

## Code Structure

### Data Preparation
- **tweets_dataset_file1.csv** and **tweets_dataset_file2.csv**: Raw tweet data.
- **Data Preparation.ipynb**: Data cleaning, tokenization, and preprocessing.
- **Word Embedding.ipynb**: Word embedding using TF-IDF.

### Kmeans Clustering
- **Kmeans Clustering.ipynb**: K-Means clustering algorithm for baseline comparison.

### AP with AC Clustering
- **AP Clustering.ipynb**: Affinity Propagation clustering algorithm.

### Statistical Analysis
- **Results.xlsx**: Clustering results and evaluation metrics.
- **Statistical Analysis.ipynb**: Jupyter notebook for statistical analysis and visualization.

## Usage
Open and run the notebooks in the following order:
1. **Data Preparation.ipynb**
2. **Word Embedding.ipynb**
3. **Kmeans Clustering.ipynb** (for baseline comparison)
4. **AP Clustering.ipynb**
5. **Statistical Analysis.ipynb** (for results analysis and visualization)

## Note
This project uses a baseline comparison with K-Means clustering to assess the performance of Affinity Propagation in sentiment analysis.
