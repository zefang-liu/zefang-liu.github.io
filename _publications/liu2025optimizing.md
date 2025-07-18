---
title: "Optimizing External Sources for Controlled Burning Plasma in Tokamaks with Neural Ordinary Differential Equations"
authors: "<b>Zefang Liu</b>, Weston M. Stacey"
collection: publications
category: conferences
permalink: /publication/liu2025optimizing
excerpt: 'NeuralPlasmaODE is used to optimize external particle and energy sources in tokamaks by solving inverse problems that guide plasma toward desired core conditions through differentiable control.'
date: 2025-07-13
venue: 'arXiv preprint arXiv:2507.09431'
paperurl: 'https://arxiv.org/abs/2507.09431'
codeurl: 'https://github.com/zefang-liu/NeuralPlasmaODE'
citation: 'Liu, Zefang, and Weston M. Stacey. &quot;Optimizing External Sources for Controlled Burning Plasma in Tokamaks with Neural Ordinary Differential Equations.&quot; <i>arXiv preprint arXiv:2507.09431</i> (2025).'
---

**Abstract**

Achieving controlled burning plasma in tokamaks requires precise regulation of external particle and energy sources to reach and maintain target core densities and temperatures. This work presents an inverse modeling approach using a multinodal plasma dynamics model based on neural ordinary differential equations (Neural ODEs). Given a desired time evolution of nodal quantities such as deuteron density or electron temperature, we compute the external source profiles, such as neutral beam injection (NBI) power, that drive the plasma toward the specified behavior. The approach is implemented within the NeuralPlasmaODE framework, which models multi-region, multi-timescale transport and incorporates physical mechanisms including radiation, auxiliary heating, and internodal energy exchange. By formulating the control task as an optimization problem, we use automatic differentiation through the Neural ODE solver to minimize the discrepancy between simulated and target trajectories. This framework transforms the forward simulation tool into a control-oriented model and provides a practical method for computing external source profiles in both current and future fusion devices.
