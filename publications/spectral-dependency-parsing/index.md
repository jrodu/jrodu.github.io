---
author: Paramveer S. Dhillon, Jordan Rodu, Michael Collins, Dean P. Foster, Lyle H. Ungar
Status: Published
date: 2012-07-01
slug: spectral-dependency-parsing
title: "Spectral Dependency Parsing with Latent Variables"
categories: Articles
tags:
- Text Analysis
details: <em>Proceedings of the 2012 Joint Conference on Empirical Methods in Natural Language Processing and Computational Natural Language Learning</em>
link: https://aclanthology.org/D12-1019
---

Recently there has been substantial interest in using spectral methods to learn generative sequence models like HMMs. Spectral methods are attractive as they provide globally consistent estimates of the model parameters and
are very fast and scalable, unlike EM methods, which can get stuck in local minima. In this paper, we present a novel extension of this class of spectral methods to learn dependency tree structures. We propose a simple
yet powerful latent variable generative model for dependency parsing, and a spectral learning method to efficiently estimate it. As a pilot experimental evaluation, we use the spectral tree probabilities estimated by our model
to re-rank the outputs of a near state-of-theart parser. Our approach gives us a moderate reduction in error of up to 4.6% over the baseline re-ranker.
