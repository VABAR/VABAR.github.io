---
layout: page
title: "VIBASS3 - Invited Course"
subheadline: "Applied Bayesian Computation: The NIMBLE Platform for Hierarchical Modeling and MCMC"
meta_teaser: "VIBASS3 Invited Course"
teaser: VIBASS3 Invited Course
header:
  title: VIBASS 3
  image_fullwidth: header_vibass18.png
  caption: Registration and call for papers
  caption_url: http://congresos.adeituv.es/VIBASS3/
image:
  #thumb: widget_vibass2.png
  #homepage: vibass2.jpg
categories: events
---

![NIMBLE]({{ site.urlimg }}nimble-logo-oval-small.png)

This course (12 hours) is provided by [__Daniel Turek__](https://danielturek.weebly.com), Assistant Professor of Statistics, Williams College and member of the [`NIMBLE`](https://r-nimble.org/) Development Team.

![image]({{ site.urlimg }}daniel_turek.jpg) 

- Audience

    Statisticians and applied researchers with strong interest in quantitative analysis

- Abstract

    This workshop provides a hands-on introduction to Bayesian analyses of hierarchical models using NIMBLE.  The NIMBLE platform (r-nimble.org) is a new system for flexible programming of algorithms that builds on the BUGS language for declaring hierarchical models. NIMBLE provides a flexible system for MCMC and other statistical algorithms which operate on user-specified models.  NIMBLE operates within R, but dynamically generates C++ code to achieve fast computation.  This workshop will introduce the NIMBLE system, and provide hands-on experience with Bayesian analyses of various applied modeling examples. 

    The first part of the workshop will cover creating a hierarchical model in NIMBLE, and fitting the model using a basic MCMC. This functionality is similar to that provided by other MCMC systems such as WinBUGS, JAGS, or Stan, although NIMBLE provides significant flexibility in the specification of the MCMC algorithm.  After learning the basics of NIMBLE's MCMC engine, we will discuss how NIMBLE permits modification of the MCMC -- changing samplers and specifying joint sampling of parameters -- to improve sampling performance.   We will learn how to modify the MCMC algorithm in NIMBLE, and assess sampling efficiency, MCMC convergence, and model comparisons.

    The second part of the workshop will introduce how to extend the hierarchical modeling syntax with user-defined distributions and user-defined functions.  These abilities provide great flexibility in specifying a statistical model of interest, and can often lead to significant performance improvements.  This will permit a brief exploration of the NIMBLE programming system, which supports writing new statistical algorithms, including MCMC samplers, using a subset of the R language.  Through examples, we will see how user-defined functions, distributions, and algorithms can be used in hierarchical models and in NIMBLE's MCMC engine.
