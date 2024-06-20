---
author: Xiaoyuan Ma, Tianyuan Zhou, Jordan Rodu
Status: Submitted
sort_date: 2024-06-08
slug: lhgm
title: Locally Hierarchical Graphical Models
categories: Articles
tags:
- Statistics
- Markov networks
details: Submitted
---

Markov networks, constructed from RNA sequencing data, encode the dependency structure between genes, which is essential for gene association detection and targeted drug development. The graphical lasso and its variants, including the Poisson graphical lasso, represent the state-of-the-art for building Markov networks. However, these methods assume a certain homogeneity in the number of associations for each gene across the network, expressed through a globally optimal sparsity penalty. We propose a method we called Locally Hierarchical Graphical Models (LHGM) which puts a prior on the sparsity instead of controlling sparsity through a lasso.  We estimate the LHGM through an algorithm we call Adaptive Search by Lasso. We highlight the superior performance of LHGM on heterogeneous data through both simulation and application on TCGA-UCEC data.