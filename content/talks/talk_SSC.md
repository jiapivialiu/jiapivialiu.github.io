---
title: "Presentation at SSC 2024, Canada"
date: 2024-06-03
layout: "talks"
url: "/talks/talk_SSC/"
summary: The 51st Annual Meeting of the Statistical Society of Canada at Memorial University of Newfoundland, St. John’s, NB, Canada
---

### *Presentation Topic*
  - *RtEstim: Effective Reproduction Number Estimation With Trend Filtering*

### *Presentation [Slides](https://docs.google.com/presentation/d/1PCo49L6WOxv4vvAaegffH9j_HZZ-sAYXqxmRC5jMjtE/edit?usp=sharing)*

### *Presentation Abstract*
  - To understand the transmissibility and spread of infectious diseases, epidemiologists turn to estimates of the instantaneous reproduction number. While many estimation approaches exist, their utility may be limited. Challenges of surveillance data collection, model assumptions that are unverifiable with data alone, and computationally inefficient frameworks are critical limitations for many existing approaches. We propose a discrete spline-based approach that solves a convex optimization problem—Poisson trend filtering—using the proximal Newton method. It produces a locally adaptive estimator for instantaneous reproduction number estimation with heterogeneous smoothness. Our methodology remains accurate even under some process misspecifications and is computationally efficient, even for large-scale data. The implementation is easily accessible in a lightweight R package *rtestim*.
