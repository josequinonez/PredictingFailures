# PredictingFailures
Use of machine learning to prevent failures in a conditional operating environment

This exercise demonstrates the use of machine learning to identify a normal operational threshold to prevent failures.

There are two approaches:
- comparing the Mahalanobis distance from each data point to the normal group centroid
- comparing the mean absolute error from the error loss from each data point to the predicted data point using a Neural Network Autoencoder 

#### Dataset
https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#turbofan

This exercise uses the second data set.

#### Source code:
https://towardsdatascience.com/machine-learning-for-anomaly-detection-and-condition-monitoring-d4614e7de770
