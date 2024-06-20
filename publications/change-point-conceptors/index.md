---
author: Noah Gade, Jordan Rodu
Status: Submitted
sort_date: 2024-06-12
slug: change-point-conceptors
title: Change Point Detection With Conceptors
categories: Articles
tags:
- Statistics
- Conceptors
- Change point detection
details: Submitted
---

Offline change point detection seeks to identify points in a time series where the data generating process changes. This problem is well studied for univariate i.i.d. data, but becomes challenging with increasing dimension and temporal dependence. For the at most one change point problem, we propose the use of a conceptor matrix to learn the characteristic dynamics of a specified training window in a time series. The associated random recurrent neural network acts as a featurizer of the data, and change points are identified from a univariate quantification of the distance between the featurization and the space spanned by a representative conceptor matrix. This model agnostic method can suggest potential locations of interest that warrant further study. We prove that, under mild assumptions, the method provides a consistent estimate of the true change point, and quantile estimates for statistics are produced via a moving block bootstrap of the original data. The method is tested on simulations from several classes of processes, and we evaluate performance with clustering metrics, graphical methods, and observed Type 1 error control. We apply our method to publicly available neural data from rats experiencing bouts of non-REM sleep prior to exploration of a radial maze.