# DC-PINNs
DC-PINNs
This repository contains the implementation of:

Hoshisashi, K., Phelan, C. E., & Barucca, P. "Physics-Informed Neural Networks for Derivative-Constrained PDEs." In ICML 2024 AI for Science Workshop.
link: https://openreview.net/forum?id=9pFHmyx4Sh

## Abstract

Physics-Informed Neural Networks (PINNs) have emerged as a promising approach for solving partial differential equations (PDEs) using deep learning. However, standard PINNs do not address the problem of constrained PDEs, where the solution must satisfy additional equality or inequality constraints beyond the governing equations. In this implementation, we introduce Derivative-Constrained PINNs (DC-PINNs), a novel framework seamlessly incorporating constraint information into the PINNs training process. DC-PINNs employ a constraint-aware loss function that penalizes constraint violations while minimizing the PDE residual. Key components include self-adaptive loss balancing techniques that automatically tune the relative weighting of each term, enhancing training stability, and using automatic differentiation to compute exact derivatives efficiently.
