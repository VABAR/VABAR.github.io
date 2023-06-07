---
layout: page
title: "VIBASS6 - Invited Talks"
subheadline: "July 14, 2023"
meta_teaser: "Invited Talks"
teaser: Invited Talks
header:
  title: VIBASS6 - Invited Talks
  image_fullwidth: header_vibass18.png
  caption: VIBASS 6 is full. Register on the waiting list.
#  caption: Registration form
  caption_url: https://congresos.adeituv.es/VIBASS6/inscripcion/
image:
  thumb: widget_vibass6.png
  homepage: vibass6.jpg
categories: events
---


## Extreme joint dependencies using nonparametric copulas

This talk introduces copulas as a very useful statistical tool to model complex joint dependencies.
Copulas allow the researcher to define separately the individual marginal densities from their dependence structure.
This provides a much greater degree of flexibility in specifying different multivariate distributions, avoiding the restrictive assumptions of the standard multivariate Gaussian or Student-t distributions.
We will review the main parametric copula families including the Archimedean family and the Elliptical copulas.
Some of them are especially useful in capturing the dependence in the tails of the distribution.
This can be particularly higher in many situations such as financial crises, where tail dependencies are usually more relevant than overall correlations.
However, parametric copulas can be too restrictive in practice and they may have problems capturing both lower and upper tail dependencies without losing coverage of the center area of the joint distribution.
Alternatively, we will review various nonparametric copulas in the literature like the empirical, Bernstein and other copulas based on generalized partitions of unity.
From the Bayesian point of view, only a few nonparametric copula models have been proposed and none of them are able to capture tail dependencies.
We will propose a new Bayesian nonparametric copula which can be viewed as a multivariate histogram smoothing with non-equally spaced infinite number of bins.
Thus, we impose a prior on the breakpoints and on the volume of the bins.
We will show how to express the model as an infinite mixture of beta distributions using the so-called stick-breaking representation.
A Gibbs sampling approach can be implemented to sample from the posterior and the predictive.
We illustrate the procedure using simulated and real data based on multivariate financial time series.


![image]({{ site.urlimg }}concepcion_ausin.jpg)

__Prof. Concepción Ausín__
Universidad Carlos III de Madrid, Spain
[https://sites.google.com/view/concepcion-ausin](https://sites.google.com/view/concepcion-ausin)


<hr>

## Modelling spatio-temporal variation in disease risk: Its not all about geographical adjacency

Population-level disease risk varies between different communities as well as over time, which is due to spatio-temporal variation in both environmental (e.g. air pollution) and social (e.g. socio-economic deprivation) exposures.
Quantifying this spatio-temporal variation informs public health policy, as it enables health agencies to: (i) identify the locations of high-risk sub-regions; (ii) quantify the changing nature of health inequalities; and (iii) estimate the effects of a range of “exposures” on the health of society.
These inferences are typically based on non-disclosive spatially aggregated summary data relating to the disease incidence among the populations living in a set of non-overlapping areal units, because individual-level data on disease incidence are typically not available for confidentiality reasons.
Modelling and drawing inferences from these spatially aggregated disease data is known as “disease mapping”, and the disease risks in geographically neighbouring areal units are typically similar.
This spatial autocorrelation in disease risk is typically captured by a set of spatially autocorrelated random effects within a Bayesian hierarchical model, with inference using either Markov chain Monte Carlo simulation or integrated nested Laplace approximations.
However, the assumption underlying these models that all pairs of neighbouring areas have similar disease risks is unrealistic in many urban settings, because disease risk surfaces are likely to contain locations exhibiting steep risk gradients that are known as risk boundaries.
Such boundaries may reflect the border where two different communities meet, and result in two neighbouring areas having very different disease risks.
This talk gives an overview of how spatio-temporal disease risk models can be altered to identify these risk boundaries, illustrates the loss in estimation accuracy when their presence is ignored, and presents a new approach to identifying them using a fusion of statistical spatial realignment models and edge detection algorithms from the field of computer vision.


![image]({{ site.urlimg }}duncan-lee.jpg)

__Prof. Duncan Lee__
University of Glasgow, Scotland
[https://www.gla.ac.uk/schools/mathematicsstatistics/staff/duncanlee/](https://www.gla.ac.uk/schools/mathematicsstatistics/staff/duncanlee/)
