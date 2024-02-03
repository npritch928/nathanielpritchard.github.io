---
title: "Residual Tracking and Stopping for Solving Consistent Linear Inverse Problems with Finite Domains"
collection: publications
permalink: /publications/2022-01-14_Residual_tracking_cons
excerpt: 
date: 2023-01-31
venue: 
paperurl:
preprinturl: https://arxiv.org/pdf/2201.05741.pdf
citation: 'Pritchard, N., & Patel, V. (2023). "Solving, Tracking and Stopping Streaming Linear Inverse Problems." <i>arXiv preprint arXiv:2201.05741</i>.'
note: 'preprint'
---
<b> Abstract </b>:
Consistent linear inverse problems with finite domains appear in a number of contexts ranging from differential-privacy estimation problems to iteratively sketched consistent linear systems. These linear inverse problems can be restated in the streaming context, which can then be addressed using streaming solvers. However, a streaming solver's benefits can only be realized if it can be appropriately tracked and stopped -- otherwise, the algorithm may stop before the desired accuracy is achieved, or it may run longer than necessary. Unfortunately, streaming solvers cannot access the residual norm, which is the traditional metric of progress. While streaming solvers have access to noisy estimates of the residual, such estimates need uncertainty sets to quantify their utility and reflect a user's risk preferences. Thus, in this work, we rigorously develop computationally-practical residual estimators and their uncertainty sets for a streaming solver. We then demonstrate the accuracy of our methods on a number of linear systems problems, including a large-scale collocation problem with over a million fixed points and randomly generated sampling points.

---
