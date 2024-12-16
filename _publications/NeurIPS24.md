---
title: "Achieving Near-Optimal Convergence for Distributed Minimax Optimization with Adaptive Stepsizes"
collection: publications
permalink: /publication/NeurIPS24
excerpt: 'Yan Huang, Xiang Li, Yipeng Shen, Niao He, Jinming Xu'
date: 2022-7-8
venue: 'NeurIPS 2024'
paperurl: 'https://openreview.net/pdf?id=O7IN4nsaIO'
authors: 'Yan Huang, Xiang Li, Yipeng Shen, Niao He, Jinming Xu'
---

Abstract: In this paper, we show that applying adaptive methods directly to distributed minimax problems can result in non-convergence due to inconsistency in locally computed adaptive stepsizes. To address this challenge, we propose D-AdaST, a Distributed Adaptive minimax method with Stepsize Tracking. The key strategy is to employ an adaptive stepsize tracking protocol involving the transmission of two extra (scalar) variables. This protocol ensures the consistency among stepsizes of nodes, eliminating the steady-state error due to the lack of coordination of stepsizes among nodes that commonly exists in vanilla distributed adaptive methods, and thus guarantees exact convergence. For nonconvex-strongly-concave distributed minimax problems, we characterize the specific transient times that ensure time-scale separation of stepsizes and quasi-independence of networks, leading to a near-optimal convergence rate of $\tilde{\mathcal{O}}\left( \epsilon ^{\left( -\left( 4+\delta \right) \right)} \right) $ for any small $\delta>0$, matching that of the centralized counterpart. To our best knowledge, D-AdaST is the first distributed adaptive method achieving near-optimal convergence without knowing any problem-dependent parameters for nonconvex minimax problems. Extensive experiments are conducted to validate our theoretical results.