# LDA_BERT: A Hybrid Model for Text Analysis
📚 Project Overview
The LDA_BERT project introduces a hybrid approach for text analysis, combining topic modeling (LDA) with semantic representations (BERT). This model is designed for clustering, topic analysis, and text classification tasks, providing both interpretability and accuracy by leveraging the strengths of two powerful text processing methods.

This repository contains the full implementation of the method, including text preprocessing, constructing combined vector representations, training an autoencoder for dimensionality reduction, and clustering using the K-Means algorithm.

🚀 Key Features
Hybrid Approach: Combines LDA for interpretability and BERT for semantic depth.
Combined Vector Representations: Incorporates a gamma parameter to balance topic and semantic features.
Dimensionality Reduction: Applies an autoencoder to create compact latent representations.
Clustering and Classification: Supports document grouping based on topics or classification using labeled data.
Versatility: Suitable for both unlabeled data (clustering) and labeled data (classification).
🔧 Functional Modules
Text Preprocessing:

Noise removal, stopword filtering, HTML tag removal, and tokenization.
Lemmatization and normalization of text data.
Vector Representation Generation:

LDA: Extracting topic distributions.
BERT: Generating deep semantic embeddings.
LDA_BERT: Combining LDA and BERT representations with a gamma parameter.
Autoencoder Training:

Compressing LDA_BERT vectors for enhanced efficiency.
Clustering:

Using K-Means to group documents based on latent representations.
Evaluating clustering performance with the silhouette coefficient.
Visualization:

Visualizing clusters with UMAP projections.
Creating word clouds for topic analysis.
Model Evaluation:

Measuring topic coherence with metrics like C_V and U_Mass.
Evaluating classification accuracy for labeled datasets.
📊 Results
Clustering: High silhouette coefficient scores indicate effective document grouping by topics.
Classification: The LDA_BERT method achieves superior accuracy and F1 scores compared to other approaches.
Interpretability: LDA enables analysis of key topic words, while BERT improves document separation.
