---
author: Jordan Rodu, Karen Kafadar
Status: Published
date: 2021-07-19
sort_date: 2021-07-19
slug: qqboxplot
title: The q–q Boxplot
categories: Articles
tags:
- Statistics
- visualization
details: <em>Journal of Computational and Graphical Statistics</em> 31:1, 26-39
doi: 10.1080/10618600.2021.1938586
link: https://www.tandfonline.com/doi/abs/10.1080/10618600.2021.1938586?journalCode=ucgs20
---

Boxplots have become an extremely popular display of distribution summaries for collections of data, especially when we need to visualize summaries for several collections simultaneously. The whiskers in the boxplot show only the extent of the tails for most of the data (with outside values denoted separately); more detailed information about the shape of the tails, such as skewness and "weight" relative to a standard reference distribution, is much better displayed via quantile--quantile (q-q) plots. We incorporate the q-q plot's tail information into the traditional boxplot by replacing the boxplot's whiskers with the tails from a q-q plot, and display these tails with confidence bands for the tails that would be expected from the tails of the reference distribution. We describe the construction of the "q-q boxplot" and demonstrate its advantages over earlier proposed boxplot modifications on data from economics and neuroscience, which illustrate the q-q boxplots' effectiveness in showing important tail behavior especially for large datasets. The package qqboxplot (an extension to the ggplot2 package) is available for the R programming language. Supplementary files for this article are available online.
