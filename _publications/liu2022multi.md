---
title: "A Multi-Region Multi-Timescale Burning Plasma Dynamics Model for Tokamaks"
authors: "<b>Zefang Liu</b>, Weston M. Stacey"
collection: publications
category: conferences
permalink: /publication/liu2022multi
excerpt: 'This paper develops a multi-region, multi-timescale transport model to simulate burning plasma dynamics in tokamaks, addressing energy transport and radiation effects to prevent thermal runaway instability in ITER scenarios.'
date: 2022-10-18
venue: '64th Annual Meeting of the APS Division of Plasma Physics'
confurl: 'https://meetings.aps.org/Meeting/DPP22/Session/GO05.6'
slidesurl: /files/liu2022multi_slides.pdf
codeurl: 'https://github.com/zefang-liu/NeuralPlasmaODE'
citation: 'Liu, Zefang, and Weston Stacey. &quot;A Multi-Region Multi-Timescale Burning Plasma Dynamics Model for Tokamaks.&quot; <i>APS Division of Plasma Physics Meeting Abstracts</i>. Vol. 2022. 2022.'
---

**Abstract**

A multi-region multi-timescale transport model is developed to simulate burning plasma dynamics in tokamaks. Deuterium-tritium fusion generates 3.5 MeV alpha particles, which transfer their energy mainly to core electrons. The heated electrons and lower-energy fusion alpha particles then heat core ions, which will increase the fusion reaction rate and may conceivably lead to a thermal runaway instability. Meanwhile, core energy is transported to the edge and radiated to the wall. The timescales of such processes determine the burning plasma dynamics. Our transport model considers the core, edge, scrape-off layer, and divertor as separate nodes. Alpha heating with a time delay between electrons and ions is computed. Electron cyclotron and impurity radiations are evaluated. Ion orbit loss as an edge plasma effect is also included. Diffusivity parameters in internodal transport times are calculated by machine learning algorithms. This model is validated against various DIII-D non-fusion plasmas and applied for multiple ITER operation scenarios. Simulation results indicate that radiation and transport can promptly remove extra heat from the core plasma and thereby inhibit the thermal runaway instability from fusion alpha heating in ITER.
