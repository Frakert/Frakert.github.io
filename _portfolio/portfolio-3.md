---
title: "NSGP - Non-Stationairy Gaussian Process Regression"
excerpt: "A Python implementation of NSGP <br/><img src='/images/500x300.png'>"
collection: portfolio
---

A Python implementation for Non-Stationairy Gaussian Process Regression.
GPR is a often used Bayesian regression approach, well known for the fact that it gives uncertainty with its predictions. \

GPR has some problems, 2 of the biggest are computation time (with a Big-O notation of $n^3$) and stationarity assumption. The stationarity assumption is the assumption that the properties of the GPR are constant over the entire range. In other words, length scale should be roughly equal in all regions. In many applications, like physics, this is not always the case.

This implementation of GPR allows for the lenghtscale and variance to be different over the entire range. It also uses PyTorch, allowing for GPU acceleration:

[GitHub Link](https://github.com/Frakert/NSGPR)