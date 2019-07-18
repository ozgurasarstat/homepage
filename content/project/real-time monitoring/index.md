---
date: "2016-04-27T00:00:00Z"
external_link: ""
image:
  caption: Protect your kidneys!
  focal_point: Smart
links:
- icon: arXiv
  icon_pack: fab
  name: Follow
  url: 
slides: example
summary: Real-time monitoring of incipient kidney failure, kidney graft failure, etc.
tags:
- Real-time monitoring
title: Real-time monitoring
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

This project contains a number of works mainly applied to kidney failure. 

# Incipient Renal Failure
In [Diggle, Sousa and Asar (2015)](https://academic.oup.com/biostatistics/article/16/3/522/269574) we considered 
modelling 392,870 estimated glomerular filtration 
rate (eGFR) observations from 22,910 patients living in the city of Salford in Greater 
Manchester. The model is a linear mixed-effects model with a Gaussian process term for long series of repeated measurement data. The aim is to identify high risk primary care patient in order for timely referral to secondary care. We base our methods on a clinical guideline 
that says a primary care patient should be referred to secondary care if s/he loses 
kidney functon at least at a rate of 5% per year.

# Predicting Kidney Graft Survival
In [Asar, Fournier and Dantan (2019)](https://arxiv.org/abs/1905.00816) we predict kidney graft survival for patients in the French transplant cohort, 
[DIVAT](http://www.divat.fr/en). The model is a joint model for longitudinal and 
survival data with non-Gaussian random-effects and measurement error term. 
We propose improved predictions of kidney graft survival compared to the 
model with Gaussian terms that was proposed by [Fournier et al.(2019)](https://academic.oup.com/ndt/advance-article-abstract/doi/10.1093/ndt/gfz027/5374746).
 