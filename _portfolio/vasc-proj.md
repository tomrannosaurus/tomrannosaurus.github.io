---
title: "Explaining VASC: VAE for Single-Cell RNA Sequencing"
excerpt: "Deep learning approach to dimension reduction for sparse single-cell RNA-seq data using variational autoencoders"
collection: portfolio
---

This project explores VASC, a dimension reduction method for single-cell RNA sequencing (scRNA-seq) data that uses variational autoencoders (VAEs) to handle the high sparsity and dropout events common in these datasets. Unlike traditional methods such as PCA, t-SNE, or ZIFA, VASC incorporates a zero-inflation (ZI) layer that explicitly models dropout events via a Gumbel-Softmax distribution, allowing the network to distinguish true biological zeros from technical noise.

The encoder compresses high-dimensional gene expression profiles (25,000+ genes) into a low-dimensional latent space, while the decoder reconstructs the original signal. The model is trained by minimizing a combined loss of binary cross-entropy reconstruction error and KL divergence regularization. Evaluation across 20 scRNA-seq datasets showed VASC outperforming competing methods on clustering accuracy metrics.

Keywords: Deep learning, Variational autoencoder, Single-cell RNA-seq, Dimensionality reduction, Bioinformatics

[View project](https://tomrannosaurus.com/vasc/) &nbsp;|&nbsp; [View on GitHub](https://github.com/tomrannosaurus/vasc)
