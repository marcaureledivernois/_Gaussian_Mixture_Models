# Gaussian Mixture Models

## Overview

Unsupervised. Gaussains Mixture Model (GMM) also known as "Expectation Maximization Clustering". The idea of GMM is very simple: for a given dataset,
each point is generated by linearly combining multiple multivariate Gaussians. It is a more advanced verison
of the K means clustering method because it also take into account standard deviation.

## Comparison with K Means

K-Means

    1. Hard Clustering of a point to one particular cluster.
    2. Cluster is only defined by mean.
    3. We can only have spherical clusters
    4. It makes use of the L2 norm when optimizing

Expectation-Maximization

    1. Soft Clustering(It gives a probability of any point belonging to a cluster).
    2. Cluster is defined by mean and standard deviation
    3. We can have elliptical clusters too
    4. It does not depend on L2 norm, but is based on Expectation, the probability of the point belonging to a particular cluster. This makes K-means biased towards spherical clusters.


## Credits

* [bspiering](https://github.com/brianspiering)
* Siraj Raval
* [OpenGenius IQ](https://iq.opengenus.org/expectation-maximization-clustering-algorithm/)
* [Towards Data Science](https://towardsdatascience.com/gaussian-mixture-models-and-expectation-maximization-a-full-explanation-50fa94111ddd)