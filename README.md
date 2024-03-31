# Food Clustering using Gaussian Mixture Models

#### Author: Sayan Roy
#### Date: 01/04/2024

*Note: Please refer to the files in this repository to find all of the data and notebook found in this report and much more.*
___

## Introduction
 
•	Gaussian Mixture Models (GMMs) are a type of probabilistic model used for clustering and density estimation tasks.
•	They assume that the data is generated from a mixture of several Gaussian distributions, each characterized by its mean and covariance matrix.
•	GMMs are flexible models that can capture complex data distributions and can model clusters of varying shapes and sizes.

___

## Representation

•	In a Gaussian Mixture Model, each data point is assumed to be generated by one of several Gaussian distributions, with each Gaussian representing a cluster in the data.
•	The probability density function of a GMM is a weighted sum of Gaussian distributions, where each Gaussian component contributes to the overall density with a certain weight.
•	The Company's analysts have inferred that annual members are much more profitable for the company than casual users, so they believe that the key of the company's future is depended upon maximizing the number of annual memberships. 

___

## Parameters
 
•	Means: The mean vectors of the Gaussian distributions.
•	Covariance Matrices: The covariance matrices of the Gaussian distributions, which represent the shape and orientation of the clusters.
•	Mixing Coefficients: The weights assigned to each Gaussian distribution, representing the probability of belonging to each cluster.

___

## Model Learning

•	The parameters of a Gaussian Mixture Model are typically learned using the Expectation-Maximization (EM) algorithm.
•	The EM algorithm iteratively updates the parameters to maximize the likelihood of the observed data given the model.
•	In the E-step, the algorithm computes the posterior probabilities (responsibilities) of each data point belonging to each Gaussian component.
•	In the M-step, the algorithm updates the parameters (means, covariances, and mixing coefficients) based on the current posterior probabilities.

___

## Model Learning

•	The parameters of a Gaussian Mixture Model are typically learned using the Expectation-Maximization (EM) algorithm.
•	The EM algorithm iteratively updates the parameters to maximize the likelihood of the observed data given the model.
•	In the E-step, the algorithm computes the posterior probabilities (responsibilities) of each data point belonging to each Gaussian component.
•	In the M-step, the algorithm updates the parameters (means, covariances, and mixing coefficients) based on the current posterior probabilities.

___

## Clustering and Density Estimation

•	GMMs can be used for clustering by assigning each data point to the cluster with the highest posterior probability.
•	They can also be used for density estimation by evaluating the probability density function at different points in the data space.

___

## Advantages

•	GMMs are flexible models that can capture complex data distributions and model clusters of varying shapes and sizes.
•	They provide probabilistic cluster assignments, allowing for uncertainty estimation.
•	GMMs can handle datasets with missing or incomplete data and can model overlapping clusters.

