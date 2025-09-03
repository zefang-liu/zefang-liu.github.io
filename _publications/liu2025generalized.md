---
title: "A Generalized Multinodal Model for Plasma Particle and Energy Transport"
authors: "<b>Zefang Liu</b>, Weston M. Stacey"
collection: publications
category: conferences
permalink: /publication/liu2025generalized
excerpt: 'A generalized multinodal model is introduced for toroidal plasma, enabling flexible simulation of particle and energy transport and efficient integration with reactor-scale and data-driven plasma studies.'
date: 2025-07-18
venue: 'arXiv preprint arXiv:2507.13627'
paperurl: 'https://arxiv.org/abs/2507.13627'
codeurl: 'https://github.com/zefang-liu/NeuralPlasmaODE'
citation: 'Liu, Zefang, and Weston M. Stacey. &quot;A Generalized Multinodal Model for Plasma Particle and Energy Transport.&quot; <i>arXiv preprint arXiv:2507.13627</i> (2025).'
---

**Abstract**

We present a generalized multinodal model for simulating particle and energy transport in toroidal plasma configurations, developed to support burning plasma analysis and reactor-scale modeling. Unlike fixed-node models, this formulation allows an arbitrary number of nodes, offering increased flexibility for coupling with core-edge or core-pedestal simulations. The model derives nodal balance equations for each plasma species by volume-averaging the continuity and energy conservation equations across toroidal shell nodes. Particle and energy transport terms are expressed in terms of internodal fluxes, linked to radial gradients via linear diffusion laws for particle density and temperature, respectively. The resulting transport contributions are characterized through effective particle and energy transport times, derived explicitly in terms of nodal geometry and diffusivities. This generalized framework facilitates efficient, modular implementation of radial transport dynamics in reduced-order or integrated plasma simulations, and is compatible with data-driven approaches such as NeuralPlasmaODE for model calibration and inference from experimental data.
