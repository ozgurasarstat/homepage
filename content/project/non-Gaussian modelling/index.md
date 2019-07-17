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
summary: Non-Gaussian Mixed-Effects Models.
tags:
- Non-Gaussian Modelling
title: Non-Gaussian Modelling
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

We consider the analysis of continuous repeated measurement outcomes that are collected through time, also known as longitudinal data. A standard framework for analysing data of this kind is a linear Gaussian mixed-effects model within which the outcome variable can be decomposed into fixed-effects, time-invariant and time-varying random-effects, and measurement noise. We develop methodology that, for the first time, allows any combination of these stochastic components to be non-Gaussian, using multivariate Normal variance-mean mixtures. We estimate parameters by max- imum likelihood, implemented with a novel, computationally efficient stochastic gradient algorithm. We obtain standard error estimates by inverting the observed Fisher-information matrix, and obtain the predictive distributions for the random-effects in both filtering (conditioning on past and current data) and smoothing (conditioning on all data) contexts. To implement these procedures, we intro- duce an R package, ngme. We re-analyse two data-sets, from cystic fibrosis and nephrology research, that were previously analysed using Gaussian linear mixed effects models.