---
layout: page
title: Stem Cell Dynamics and Haematopoietic System Modelling
description: Multi-scale deterministic and stochastic models of stem cell self-renewal, differentiation, and population dynamics in haematopoietic and epithelial tissues, including the mathematical underpinnings of periodic blood disorders.
img: assets/img/proj2.jpg
importance: 2
category: work
---

## Overview

The haematopoietic system produces approximately 10¹¹ blood cells per day through a tightly regulated hierarchy of stem and progenitor cells. Mathematical modelling of this system has a rich history — and our group has contributed significantly to its quantitative understanding across multiple scales, from the molecular circuits governing individual cell fate to the population-level oscillations observed in periodic blood disorders.

A central focus is the interplay between **cell heterogeneity** (different cells carry different epigenetic states), **negative feedback regulation** (circulating blood cells suppress further stem cell proliferation), and **stochastic effects** (gene expression noise, random cell divisions), and how these factors jointly shape the dynamics of the entire haematopoietic tissue.

---

## Key Research Questions

- What mathematical conditions give rise to sustained oscillations in blood cell counts, as seen in cyclic neutropenia and periodic CML?
- How does cell heterogeneity — specifically, the diversity of epigenetic states across stem cells — affect the stability and robustness of the haematopoietic system?
- What is the role of stochastic epigenetic inheritance in governing the balance between stem cell self-renewal and differentiation?
- How do cross-scale interactions between molecular circuits and population dynamics produce emergent tissue-level behaviour?

---

## Modelling Framework

Our models span multiple scales and mathematical formulations:

**Deterministic ODE/DDE systems** capture the dynamics of stem cell and mature blood cell populations under negative feedback, enabling rigorous bifurcation analysis (Hopf bifurcation, period-doubling) to identify conditions for oscillatory and chaotic dynamics.

**Delay differential equations (DDEs)** are essential for accurately describing the maturation delay between stem cell commitment and the emergence of mature circulating cells — a feature that critically determines whether the system oscillates. Our group has developed significant mathematical theory for DDEs in this biological context, including the first proof that certain classes of DDEs generate deterministic Brownian-like motion (Lei & Mackey, *Physical Review E*, 2011).

**Delay integro-differential equations** extend the DDE framework to heterogeneous cell populations, where each cell carries a continuous epigenetic state variable. The resulting infinite-dimensional dynamical system is analysed via Hopf bifurcation theory in function spaces, leading to sharp conditions on proliferation and differentiation rates for oscillatory versus stable dynamics.

**Stochastic models** (SDEs, master equations) capture cell-to-cell variability in gene expression and epigenetic state inheritance during cell division, connecting molecular stochasticity to population-level fluctuations.

---

## Representative Results

**Heterogeneous Stem Cell Regeneration and Oscillatory Dynamics** (Liang, Lei, *Communications on Applied Mathematics and Computation*, 2024): We constructed a delay integro-differential equation model incorporating continuous epigenetic heterogeneity across stem cells and stochastic epigenetic inheritance during division. Hopf bifurcation analysis revealed a counter-intuitive result: increasing cell heterogeneity can *stabilise* the system rather than destabilise it, suggesting that diversity within stem cell populations is a source of tissue robustness. This finding has implications for understanding why haematopoietic oscillations (cyclic neutropenia, periodic CML) arise and how they might be attenuated.

**Deterministic Brownian Motion from Delay Equations** (Lei, Mackey, *Physical Review E*, 2011): We demonstrated rigorously that certain differential delay equations with two unstable equilibria can generate chaotic dynamics with statistical properties — including Gaussian velocity distributions and exponential autocorrelations — that are indistinguishable from Brownian motion. This unexpected mathematical connection between deterministic DDEs and stochastic processes has implications for understanding variability in biological systems without invoking explicit stochasticity.

**Cross-Talk Between Genetic and Epigenetic Regulation in Adult Stem Cells** (Lei, Levin, Nie, *PNAS*, 2014): A multi-scale model linking intracellular gene regulatory network dynamics to population-level stem cell proliferation and differentiation demonstrated how epigenetic heterogeneity across cells can create a stable tissue that is simultaneously flexible enough to respond to injury. The model explains the quantitative relationship between stem cell pool size, regeneration rate, and tissue homeostasis under various perturbations.

**Moment Stability for Stochastic Delay Equations in Haematopoiesis** (Lei, *SIAM Journal on Applied Mathematics*, 2007): We proved rigorous stability conditions — in terms of moment Lyapunov exponents — for stochastic functional differential equations describing haematopoietic stem cell dynamics, providing the theoretical foundation for later numerical and biological work.

---

## Connection to Blood Disorders

The mathematical structures we study are directly connected to clinically observed **dynamic haematological diseases**:

- **Cyclic neutropenia** (oscillation period ~21 days): the DDE models predict oscillatory instability arising from changes in the apoptosis rate during stem cell proliferation — consistent with clinical mutations in the ELA2 gene.
- **Periodic chronic myelogenous leukaemia**: the same mathematical framework, applied to CML stem cell dynamics, predicts the longer (~70-day) oscillation period observed in some CML patients.
- **Aplastic anaemia**: parameter regimes in the model correspond to collapse of the haematopoietic stem cell compartment, allowing quantitative exploration of rescue strategies.

---

## Selected Publications

- Liang X, Lei J\*. Oscillatory dynamics of heterogeneous stem cell regeneration. *Communications on Applied Mathematics and Computation*, 2024, 6: 431–453.
- Lei J\*, Mackey MC. Deterministic Brownian motion generated from differential delay equations. *Physical Review E*, 2011, 84: 041105.
- Lei J, Levin SA, Nie Q. Mathematical model of adult stem cell regeneration with cross-talk between genetic and epigenetic regulation. *Proceedings of the National Academy of Sciences*, 2014, 111: E880–E887.
- Lei J\*. Stochastic differential delay equation, moment stability, and application to haematopoietic stem cell regulation system. *SIAM Journal on Applied Mathematics*, 2007, 67(2): 387–407.
- Jiang H, Liu JX, Song Y, Lei J\*. Quantitative modeling of stemness in single-cell RNA sequencing data: a nonlinear one-class support vector machine method. *Journal of Computational Biology*, 2024, 31(1): 41–57.
