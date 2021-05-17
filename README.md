# Pairwise Learning to Rank Approach using Light Gradient Boosting Machine (LightGBM)

Pairwise approaches look at a pair of documents at a time in the loss function. Given a pair of documents, they try and come up with the optimal ordering for that pair and compare it to the ground truth. The goal for the ranker is to minimize the number of inversions in ranking i.e. cases where the pair of results are in the wrong order relative to the ground truth.

Using Dataset From : [MQ2008](https://www.microsoft.com/en-us/research/project/letor-learning-rank-information-retrieval/)

