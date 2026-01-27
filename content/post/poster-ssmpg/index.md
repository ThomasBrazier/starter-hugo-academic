---
title: "Poster SSMPG 2025: Bayesian Deep Learning and ABC for Population Genomics Inference"
subtitle: abcneuralnet R package
date: 2025-07-12
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
I presented my work on Bayesian Deep Learning and ABC for Population Genomics Inference at the Summer School on Software and Statistical Methods for Population Genomics 2025 [workshop](https://ssmpg2025.sciencesconf.org/) in the French Alps. The poster presenting the method and the R package is [here](https://github.com/ThomasBrazier/starter-hugo-academic/blob/main/statics/uploads/poster_ssmpg2025.pdf).

Approximate Bayesian Computation (ABC) has emerged as a powerful framework for parameter inference in complex statistical models where likelihood functions are intractable. However, traditional ABC methods face significant computational challenges when dealing with high-dimensional summary statistics and complex parameter spaces. The R package **abcneuralnet** integrates Bayesian deep learning with ABC to address these challenges. We demonstrate four methodological approaches: Concrete Dropout (Gal et al 2017), Monte Carlo Dropout (Gal et al 2016), Deep Ensemble (Lakshminarayanan et al 2016), and TabNet-ABC (Arik et al 2020; Akesson et al 2022). Each method provides different strategies for uncertainty quantification and parameter inference, combining the representational power of deep neural networks with principled Bayesian inference. Through comprehensive examples, we illustrate the theoretical foundations, practical implementation, and performance characteristics of these methods for parameter inference in population genetics and related fields.