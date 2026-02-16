---
title: "Genetic Neural Networks for Coarse Scale FEM Correction"
excerpt: "BSc Thesis Predictive Maintenance <br/><img src='/images/multi_scale.jpg'>"
collection: portfolio
---

![Image showing a multiscale design.](/images/multi_scale.jpg)

This research project explored the integration of Machine Learning with Finite Element Method (FEM) simulations to address the high computational costs typically associated with fluid mechanics. The primary focus was a 1D advection-diffusion heat-flow problem, where the goal was to apply Genetic Neural Networks (GNN) to learn stabilization parameters and correct coarse-grid simulations. Using an evolutionary approach was essential because no traditional gradient for backpropagation was available—only the error between the coarse and fine-scale simulations.

The technical implementation utilized the Dolphinx and FEniCS libraries for the underlying physics simulations and the PyGAD library for the genetic algorithm framework. To enhance the model's ability to generalize, the study investigated several training strategies, including the introduction of batch-based fitness evaluation to prevent overfitting to individual data points. Further experimentation involved tuning genetic pressure by adjusting mutation rates and modifying fitness functions to prioritize the reduction of extreme prediction outliers.

The end result we were sadly dissapointing. We did not have enough time to explore all options and the Genetic algorithm was not able to learn to a sufficient degree. 

[Download the report here](/files/Multi_Physics-Evolutionary_Neural_Networks_for_coarse_scale_correction.pdf)