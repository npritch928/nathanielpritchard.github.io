---
title: "Solving, tracking and stopping streaming linear inverse problems"
collection: publications
permalink: /publications/2022-01-14_Residual_tracking_cons
excerpt: 
date: 2023-01-31
venue: Inverse Problems
paperurl: https://doi.org/10.1088/1361-6420/ad5583
preprinturl: https://arxiv.org/pdf/2201.05741.pdf
citation: 'Pritchard, N., & Patel, V. (2024). "Solving, tracking and stopping streaming linear inverse problems" <i>Inverse Problems</i>.'
note: 
---
<b> Abstract </b>:
In large-scale applications including medical imaging, collocation differential equation solvers, and estimation with differential privacy, the underlying linear inverse problem can be reformulated as a streaming problem. In theory, the streaming problem can be effectively solved using memory-efficient, exponentially-converging streaming solvers. In practice, a streaming solver's effectiveness is undermined if it is stopped before, or well-after, the desired accuracy is achieved. In special cases when the underlying linear inverse problem is finite-dimensional, streaming solvers can periodically evaluate the residual norm at a substantial computational cost. When the underlying system is infinite dimensional, streaming solver can only access noisy estimates of the residual. While such noisy estimates are computationally efficient, they are useful only when their accuracy is known. In this work, we rigorously develop a general family of computationally-practical residual estimators and their uncertainty sets for streaming solvers, and we demonstrate the accuracy of our methods on a number of large-scale linear problems. Thus, we further enable the practical use of streaming solvers for important classes of linear inverse problems.
---
