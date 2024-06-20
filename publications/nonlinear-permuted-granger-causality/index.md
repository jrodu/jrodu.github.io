---
author: Noah Gade, Jordan Rodu
Status: Submitted
sort_date: 2024-06-13
slug: nonlinear-permuted-granger-causality
title: Nonlinear Permuted Granger Causality
categories: Articles
tags:
- Statistics
- Granger Causality
details: Submitted
---

Granger causal inference is a contentious but widespread method used in fields ranging from economics to neuroscience. The original definition addresses the notion of causality in time series by establishing functional dependence conditional on a specified model. Adaptation of Granger causality to nonlinear data remains challenging, and many methods apply in-sample tests that do not incorporate out-of-sample predictability, leading to concerns of model overfitting. To allow for out-of-sample comparison, a measure of functional connectivity is explicitly defined using permutations of the covariate set. Artificial neural networks serve as featurizers of the data to approximate any arbitrary, nonlinear relationship, and consistent estimation of the variance for each permutation is shown under certain conditions on the featurization process and the model residuals. Performance of the permutation method is compared to penalized variable selection, naive replacement, and omission techniques via simulation, and it is applied to neuronal responses of acoustic stimuli in the auditory cortex of anesthetized rats. Targeted use of the Granger causal framework, when prior knowledge of the causal mechanisms in a dataset are limited, can help to reveal potential predictive relationships between sets of variables that warrant further study.