# Unsupervised-Machine-Learning-for-Text-Clustering

The objective is to cluster text corpus into groups based on contextual similarity using a Machine Learning algorithm and determine the correlation between them

**Dataset**

The [Amazon Food Reviews](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews) dataset from Kaggle was shortlisted for the task. The dataset has nearly 500,000 records over a span of 10 years and includes information on product and user information, ratings, and a plain text review

**Exploratory Data Analysis**

Duplicates records were dropped, ratings were assigned positive or negative labels; noise, punctuations and stop words were removed

**Clustering**

For clustering an unsupervised, greedy algorithm was used. Checked for an ideal value to determine the number of clusters by plotting an elbow curve. Transformed text corpus to feature vectors and fed them to the KMeans algorithm

Silhouette score determined cluster corelation and the scatter plot was a straight line parallel to Y-axis
