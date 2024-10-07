---
title: "Application of Nonparametric Regression in Epidemiology"
date: 2023-12-31
layout: "portfolio"
url: "/portfolio/project_TF"
summary: Publication on PLOS Computational Biology (Method) in August, 2024
---

*Liu J, Cai Z, Gustafson P, McDonald DJ (2024) rtestim: Time-varying reproduction number estimation with trend filtering. PLOS Computational Biology 20(8): e1012324. https://doi.org/10.1371/journal.pcbi.1012324*

This is a project of application on time-varying reproduction number estimation using 
convex optimization and proximal algorithm solvers. 

- We built a nonparametric regression model with trend filtering penalty to estimate instantaneous reproduction
number, a key tool to reveal the transmissibility of infectious diseases.

- We developed a method using proximal Newton method, ADMM, and dynamic programming to solve the problem.

- We wrote the main manuscript and all supplementary documents and conducted the experimental study.

- We developed a lightweight and computationally efficient R package rtestim (coded from scratch).

### Source Code 

- All related data can be found in [this](https://github.com/jiapivialiu/rt-est-manuscript) GitHub repository.

### Software Development

- R package for time-varying reproduction number estimation for infectious disease [rtestim](https://dajmcdon.github.io/rtestim/) with core algorithms developed in C++.

### Toolkit for the Project

- C, C++, R languages.
- R Packages: Rcpp, RcppArmadillo, RcppEigen, cpp11, ggplot2, batchtools, etc.
- Linux.
- Computing Resource: Compute Canada.
- R Studio, VScode.
- LaTeX, RMarkdown.