---
title: "Towards Practical Large-scale Randomized Iterative Least Squares Solvers through Uncertainty Quantification"
collection: publications
permalink: /publications/2022-08-09_Towards_practical_large
excerpt: 
date: 2022-08-09
venue: Siam Journal of Uncertainty Quantification 
paperurl: https://epubs.siam.org/doi/10.1137/22M1515057
preprinturl: https://arxiv.org/abs/2208.04989
citation: 'Pritchard, N., & Patel, V. (2023). Towards Practical Large-Scale Randomized Iterative Least Squares Solvers through Uncertainty Quantification. <i>SIAM/ASA Journal on Uncertainty Quantification,</i> 11(3), 996-1024.' 
note: 
---
<b> Abstract </b>:
As the scale of problems and data used for experimental design, signal processing and data assimilation grow, the oft-occuring least squares subproblems are correspondingly growing in size. As the scale of these least squares problems creates prohibitive memory movement costs for the usual incremental QR and Krylov-based algorithms, randomized least squares problems are garnering more attention. However, these randomized least squares solvers are difficult to integrate application algorithms as their uncertainty limits practical tracking of algorithmic progress and reliable stopping. Accordingly, in this work, we develop theoretically-rigorous, practical tools for quantifying the uncertainty of an important class of iterative randomized least squares algorithms, which we then use to track algorithmic progress and create a stopping condition. We demonstrate the effectiveness of our algorithm by solving a 0.78 TB least squares subproblem from the inner loop of incremental 4D-Var using only 195 MB of memory.

---
