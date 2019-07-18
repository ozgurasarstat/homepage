---
date: "2016-04-27T00:00:00Z"
external_link: ""
image:
  caption: To be or not to be Gaussian!
  focal_point: Smart
links:
- icon: arXiv
  icon_pack: fab
  name: Follow
  url: https://arxiv.org/abs/1804.02592
slides: example
summary: Non-Gaussian Modelling.
tags:
- Non-Gaussian Modelling
title: Non-Gaussian Modelling
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

This project consists of a number of methodological works of linear mixed-effects models and joint modelling of longitudinal and time-to-event outcomes. 

# Linear-Mixed Effects Models

In [Asar et al. (2016)](https://onlinelibrary.wiley.com/doi/abs/10.1002/bimj.201500270) we consider a linear mixed-effects model that assumes observed outcomes are underlying signal plus additive noise. Underlying signal is de-composed as fixed-effects, time-invariant 
random-effects, a stochastic process. We assume a multivariate t distribution for the repeated outcomes of a specific subject. The R package [lmenssp](https://cran.r-project.org/web/packages/lmenssp/index.html) implements the methods. The methodology improves on the widely used multivariate Gaussian model, yet it has some drawbacks due to formulating the t distribution with a single mixing variable for a specific subject. 

In [Asar et al.(2019a)](https://arxiv.org/abs/1804.02592) we de-coupled the mixing varible and proposed a computationally efficient algorithm for maximum likelihood inference especially to analyse tall data-sets, i.e. data-sets with many rows. De-coupling allows us dropping the dependence between the random terms of the model. The R package [ngme](https://bitbucket.org/davidbolin/ngme/src/default/) implements the proposed methods. 

# Joint Modelling of Longitudinal and Time-to-Event Outcomes

In [Asar et al.(2019b)](https://arxiv.org/abs/1905.00816) we considered joint modelling of longitudinal and survival outcomes with t distributed random-effects and error terms. 
Random-effects and error terms were assumed to be independent and error terms were assumed to be serially indpendent. To the best of our knowledge this is the first work that proposed such a flexible joint model. The R package [robjm](https://github.com/ozgurasarstat/robjm) implements the methods for modelling and dynamic predictions. 

In [Asar et al.(2019c)]() we further extend the model of [Asar et al.(2019b)](https://arxiv.org/abs/1905.00816) by allowing the degrees-of-freedom and scale parameters of the t distribution for the error term being time-varying. 
This is a likely scenario where data have different frequencies of outliers through time. 
Related methods are also implemented in the R package [robjm](https://github.com/ozgurasarstat/robjm). 
This work is nearly finished and will be available from arXiv soon!