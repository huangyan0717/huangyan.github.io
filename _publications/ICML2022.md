---
title: "Tackling Data Heterogeneity: A New Unified Framework for Decentralized SGD with Sample-induced Topology"
collection: publications
permalink: /publication/ICML2022
excerpt: 'Yan Huang, Ying Sun, Zehan Zhu, Changzhi Yan, Jinming Xu'
date: 2022-7-8
venue: 'The 39th International Conference on Machine Learning'
paperurl: 'https://arxiv.org/pdf/2207.03730.pdf'
authors: 'Yan Huang, Ying Sun, Zehan Zhu, Changzhi Yan, Jinming Xu'
---

Abstract: We develop a general framework unifying several gradient-based stochastic optimization methods for empirical risk minimization problems both in centralized and distributed scenarios. The framework hinges on the introduction of an augmented graph consisting of nodes modeling the samples and edges modeling both the inter-device communication and intra-device stochastic gradient computation. By designing properly the topology of the augmented graph, we are able to recover as special cases the renowned Local-SGD and DSGD algorithms, and provide a unified perspective for variance-reduction (VR) and gradient-tracking (GT) methods such as SAGA, Local-SVRG and GT-SAGA. We also provide a unified convergence analysis for smooth and (strongly) convex objectives relying on a proper structured Lyapunov function, and the obtained rate can recover the best known results for many existing algorithms. The rate results further reveal that VR and GT methods can effectively eliminate data heterogeneity within and across devices, respectively, enabling the exact convergence of the algorithm to the optimal solution. Numerical experiments confirm the findings in this paper.

