## Getting Optimal Parameters for HNSW Index
This repository is dedicated to demonstrating how to find the optimal parameters for the Hierarchical Navigable Small World (HNSW) index to achieve a high recall rate in nearest neighbor searches.

## **Overview**
Recall is a key performance metric in search algorithms, representing the proportion of relevant items correctly retrieved by the algorithm. In the context of nearest neighbor search, recall measures the fraction of true nearest neighbors that are present in the top-k results returned by the index. A recall of 1 means that all true nearest neighbors are retrieved, while a recall of 0 indicates none are found.

## **Purpose**
The goal of this repository is to explore and optimize the parameters of the HNSW index to maximize recall. The HNSW index is widely used for efficient nearest neighbor search in high-dimensional spaces, but its performance heavily depends on its parameter settings. We will focus on tuning three critical parameters:

M: The number of neighbors to consider during the construction of the index.
ef: The size of the dynamic list used during the search for nearest neighbors.
ef_construction: The size of the dynamic list used during the construction phase of the index.
By adjusting these parameters, we aim to improve the recall rate of the HNSW index for a given dataset.

## **Methodology**
We will use a synthetic dataset to perform this optimization. The process involves:

Generating a Synthetic Dataset: We will create a synthetic dataset to simulate a high-dimensional space for nearest neighbor searches.
Brute-Force Search for Benchmarking: A brute-force search will be conducted to establish a baseline for the recall rate.
Parameter Tuning: Starting with initial values for M, ef, and ef_construction, we will iteratively adjust these parameters to observe their impact on recall.
Recall Calculation: The recall of the HNSW index will be computed for different parameter settings to identify the optimal configuration.


This repository provides a comprehensive guide to optimizing the HNSW index parameters for high recall in nearest neighbor searches. By fine-tuning M, ef, and ef_construction, users can achieve better search performance and ensure more accurate results in their applications.

Feel free to contribute, suggest improvements, or report any issues you encounter. Happy optimizing!


