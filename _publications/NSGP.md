---
title: "Reduced Order Models for Non-Newtonian Fluids Using Non-Stationary Gaussian Process Regression"
collection: publications
category: not-publshied
permalink: /publication/NSGP
excerpt: 'This (non-published) paper was written for team internship and explores how adaptive learning can be used to reduce the need for data in reduced order moddeling approaches for FEM simulations. The result is a python package for non-stationairy Gaussian Process Regression (NSGPR) and a method which needs a third of the data to gain the same accuracy.'
date: 2025-06-16
paperurl: 'https://academicpages.github.io/files/ROM_NSGP_Paper.pdf'
---

*Note that this paper was never published, but made for educational purposes. I do however believe it to be of sufficient quality to present it.*

For the Master AI & Engineering Systems, an inter-disciplinairy team internship is required. Over the course of 20 weeks, a team with different nationalities and background worked together on the project. My colaborators for this project were: Sven Bendermacher, Vicky Hufken and Wybe Sesink.

For an easier introduction, the slides for a presentation can be found [Here](/files/Slides_NSGP.pdf)

See the Abstract below :

Abstract
=============
This study developed an uncertainty-driven adap-tive  sampling  framework  for  data-efficient  reduced-ordermodels  (ROMs)  of  non-Newtonian  fluid  flows,  leveraging non-stationary  Gaussian  Process  Regression  (NSGPR).  The objective  was  to  enhance  ROMs  performance  in  scenarios with  scarce  or  computationally  expensive  data,  like Finite Element Method (FEM) simulations. We applied Proper Orthogonal  Decomposition  (POD)  to  reduce  high-dimensional FEM  solutions  to  a  set  of  coefficients,  which  were  then predicted  by  NSGPR,  providing  both  a  mean  prediction and  an  uncertainty  measure  to  guide  subsequent  adaptive sampling.The forward problem demonstrated that NSGPR with adaptive  sampling  achieved  a  similar  mean  absolute  error  using only one-third of the data compared to linear sampling. For the  inverse  problem,  the  framework  successfully  inferred fluid  parameters  from  limited  experimental  measurements, yielding accurate posterior distributions which accounted for model  and  experimental  uncertainty. The  method  is  equation-free  and  non-intrusive,  making  it compatible  with  existing  simulation  workflows.  It  provides a  promising  solution  for  parameter  estimation  in  nonlinear, data-scarce systems across engineering and physical sciences, significantly reducing the computational burden of high-resolution simulations.

[Paper pdf download](/files/ROM_NSGP_Paper.pdf)