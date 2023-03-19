---
layout: archive
title: "Modeling Colorectal Cancer Gene Expression Distributions using Mixture Models"
# permalink: /research/ml4fg.md
collection: research
excerpt: "Research Project for the Columbia University Course COMS 4762: ML for Functional Genomics"
author_profile: true
order_number: 3
---

**Authors:**
* Shomik Ghose -- [email](mailto:sg3789@columbia.edu)
* Austin Tao -- [email](mailto:alt2177@columbia.edu)

## Description

This was a semester-long research project for [Prof. David Knowles'](https://davidaknowles.github.io/) Columbia University course COMS W4762: Machine Learning for Functional Genomics. Our code is available via [github](https://github.com/shogho0/ml4fgfinalproject), the final report is available [here](/files/ML4FG_Final_Report.pdf), and our presentation slides are [here](/files/ML4FG_slides.pdf).

## Abstract

We implemented mixture models, an unsupervised machine learning technique, to best fit continuous gene expression distributions. Throughout our research, we both applied existing packages (for Gaussian and student-t mixture models) and developed our own implementations (for Gaussian and Shifted Asymmetric Laplace mixture models) to fit our data. Ultimately, we found that while our own implementations were moderately effective, a weighted average of Gaussian and student-t mixture models using the existing packages (but using a novel method to analytically determine weights) were best at fitting the distributions. We also developed our own model selection metrics, as we found that standard metrics such as Bayesian Information Criterion (BIC) did not truly identify which models best fit the distribution, especially for non-normal distributions.

