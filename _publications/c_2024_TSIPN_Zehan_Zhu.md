---
title: "R-FAST: Robust Fully-Asynchronous Stochastic Gradient Tracking over General Topology"
collection: publications
label: c_2024_TSIPN_Zehan_Zhu
excerpt: 'Zehan Zhu, Ye Tian, Yan Huang, Jinming Xu, Shibo He'
date: 2024-08-30
venue: 'IEEE Transactions on Signal and Information Processing over Networks'
paperurl: '[https://arxiv.org/pdf/2307.11617.pdf](https://arxiv.org/html/2307.11617v2)'
authors: 'Zehan Zhu, Ye Tian, Yan Huang, Jinming Xu, Shibo He'
---

Abstract: We propose a Robust Fully-Asynchronous Stochastic Gradient Tracking method (R-FAST) for distributed machine learning problems over a network of nodes, where each node performs local computation and communication at its own pace without any form of synchronization. Different from existing asynchronous distributed algorithms, R-FAST can eliminate the impact of data heterogeneity across nodes on convergence performance and allow for packet losses by employing a robust gradient tracking strategy that relies on properly designed auxiliary variables for tracking and buffering the overall gradient vector. Moreover, the proposed method utilizes two spanning-tree graphs for communication so long as both share at least one common root, enabling flexible designs in communication topologies. We show that R-FAST converges in expectation to a neighborhood of the optimum with a geometric rate for smooth and strongly convex objectives; and to a stationary point with a sublinear rate for general non-convex problems. Extensive experiments demonstrate that R-FAST runs 1.5-2 times faster than synchronous benchmark algorithms, such as Ring-AllReduce and D-PSGD, while still achieving comparable accuracy, and outperforms the existing well-known asynchronous algorithms, such as AD-PSGD and OSGP, especially in the presence of stragglers.


