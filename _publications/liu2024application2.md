---
title: "Application of Neural Ordinary Differential Equations for ITER Burning Plasma Dynamics"
authors: "<b>Zefang Liu</b>, Weston M. Stacey"
collection: publications
category: conferences
permalink: /publication/liu2024application2
excerpt: 'A neural ODE-based burning plasma dynamics model, NeuralPlasmaODE, simulates energy transfer in ITER plasmas for both inductive and non-inductive scenarios.'
date: 2024-08-01
venue: 'AAAI 2025 Workshop on AI to Accelerate Science and Engineering (AI2ASE)'
paperurl: 'https://arxiv.org/abs/2408.14404'
codeurl: 'https://github.com/zefang-liu/NeuralPlasmaODE'
posterurl: /files/liu2024application2_poster.pdf
citation: 'Liu, Zefang, and Weston M. Stacey. &quot;Application of Neural Ordinary Differential Equations for ITER Burning Plasma Dynamics.&quot; <i>arXiv preprint arXiv:2408.14404</i> (2024).'
---

**Abstract**

The dynamics of burning plasmas in tokamaks are crucial for advancing controlled thermonuclear fusion. This study introduces the NeuralPlasmaODE, a multi-region multi-timescale transport model to simulate the complex energy transfer processes in ITER deuterium-tritium (D-T) plasmas. Our model captures the interactions between energetic alpha particles, electrons, and ions, which are vital for understanding phenomena such as thermal runaway instability. We employ neural ordinary differential equations (Neural ODEs) for the numerical derivation of diffusivity parameters, enabling precise modeling of energy interactions between different plasma regions. By leveraging transfer learning, we utilize model parameters derived from DIII-D experimental data, enhancing the efficiency and accuracy of our simulations without training from scratch. Applying this model to ITER's inductive and non-inductive operational scenarios, our results demonstrate that radiation and transport processes effectively remove excess heat from the core plasma, preventing thermal runaway instability. This study underscores the potential of machine learning in advancing our understanding and control of burning plasma dynamics in fusion reactors.
