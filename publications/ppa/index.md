---
author: Jordan Rodu, Alexandra F Dejong Lempke
Status: Submitted
sort_date: 2024-06-16
slug: ppa
title: Plot panel analysis
categories: Articles
tags:
- Statistics
- visualization
details: Submitted
---

Modern data analysis frequently requires characterizing a large collection of observations composed of multiple data points (e.g. collections of time series, scatterplots, or networks).  Data visualization is an essential tool for exploring such data, but novel techniques are needed to overcome challenges associated with visualizing populations of these observations, such as overplotting.  This manuscript proposes a novel approach that we call plot panel analysis (PPA).  PPA is an interactive small multiples technique that promotes clarity in simultaneous visual access to the entire population of observations, efficient bookkeeping, and flexible feature examination and characterization.  We call the mechanism that facilitates these objectives ``interactive selection.'' 
 Motivated by the rise in popularity of and challenges working with data from wearable sensors in Kinesiology studies, we demonstrate the effectiveness of PPA with a simple, easy-to-understand simulated example based on real data from Runscribe sensors. A usable prototype R Shiny application, ppa, is provided.