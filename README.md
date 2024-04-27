# Data-Representations-and-Clustering

This repository contains the code and data for the second project of the ECE 219 Large-Scale Data Mining course at UCLA. The goal of this project is to explore feature extraction techniques and clustering algorithms on text and image data.

## Project Overview

The project is divided into three main parts:

1. **Clustering on Text Data**: Applying various feature extraction methods like TF-IDF, SVD, NMF, and UMAP on the 20 Newsgroups dataset, followed by clustering algorithms like K-Means, Agglomerative Clustering, and HDBSCAN.

2. **Deep Learning and Clustering of Image Data**: Extracting features from the TF Flowers dataset using a pre-trained VGG network, followed by dimensionality reduction techniques like SVD, UMAP, Autoencoders, and clustering.

3. **Clustering using Image and Text Data**: Exploring multimodal clustering using the CLIP model on the Pokemon dataset, which contains both images and text descriptions.

## Dataset

The project utilizes the following datasets:

- **20 Newsgroups**: A collection of approximately 20,000 documents partitioned across 20 different newsgroups (discussion forums).
- **TF Flowers**: A dataset consisting of images of five types of flowers.
- **Pokemon Dataset**: A dataset containing images and metadata of different Pokemon.

## Usage

1. Clone the repository
2. Download the datasets (links provided in the project spec)
3. Run the Jupyter notebook

The notebooks are self-contained and provide detailed explanations of each step.

## Results

The project report `report.pdf` describes the implemented approaches, analyzes the results, and provides visualizations of the clustering performance on the datasets.

## Acknowledgments

I thank Professor Vwani Roychowdhury and the course staff of ECE 219 for their guidance on this project.
