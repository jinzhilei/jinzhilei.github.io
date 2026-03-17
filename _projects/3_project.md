---
layout: page
title: Epigenetic Regulation and Cell-Fate Decisions
description: Mathematical modelling of cell-type transitions, Waddington landscape dynamics, epigenetic inheritance noise, and the role of epigenetic instability in cancer drug resistance.
img: assets/img/proj3.jpg
importance: 3
category: work
---

## Overview

Every cell in the human body carries the same genomic sequence, yet the hundreds of distinct cell types differ dramatically in morphology, function, and gene expression. This diversity is encoded in the **epigenome** — a dynamic layer of chromatin modifications (histone methylation, acetylation, DNA methylation) that modulates gene accessibility and expression without altering the underlying DNA sequence. Understanding how the epigenome governs cell identity, mediates cell-fate transitions, and — when dysregulated — drives cancer initiation and drug resistance is one of the central problems in modern biology.

Our group develops mathematical frameworks to describe epigenetic dynamics quantitatively, bridging the gap between molecular mechanisms (individual histone modification events, stochastic inheritance during cell division) and macroscopic observables (cell type distributions, tissue composition, drug sensitivity landscapes).

---

## Key Research Questions

- How do stochastic epigenetic modifications during cell division drive spontaneous cell-fate transitions — differentiation, de-differentiation, and transdifferentiation — without external signals?
- What is the shape of the Waddington epigenetic landscape for specific cell-type systems, and how can it be computed from mechanistic models?
- How does epigenetic instability in cancer cells promote the emergence of drug-tolerant persister (DTP) cells, and what treatment schedules best exploit this vulnerability?
- Can we design targeted interventions (epigenetic drugs, transcription factor overexpression) that predictably redirect cell fate towards desired outcomes in regenerative medicine?

---

## Modelling Framework

**Multi-scale hybrid models** form the backbone of this research direction. At the molecular scale, we track the stochastic dynamics of key histone modifications (H3K4me3 as an active mark, H3K27me3 as a repressive mark) at each gene locus, modelled as continuous-time Markov chains or stochastic differential equations. At the cell scale, gene expression levels are determined by these epigenetic states through sigmoidal activation functions, and cell identity is classified by the attractor in the gene regulatory network that the cell inhabits. At the population scale, we track the fractions of cells in each epigenetic state using delay integro-differential equations or PDE models.

A key biological insight embedded in these models is that **epigenetic states are stochastically inherited during cell division** — daughter cells receive a noisy copy of the parental chromatin state — and this noise is the fundamental driver of spontaneous cell-fate transitions. The rate and direction of transitions depend on the epigenetic landscape, which in turn depends on the concentrations of chromatin-modifying enzymes and transcription factors.

---

## Representative Results

**Dynamics of Cell-Type Transition Mediated by Epigenetic Modifications** (Huang, Situ, Lei, *Journal of Theoretical Biology*, 2024): We constructed a three-scale model integrating (i) stochastic histone modification kinetics, (ii) gene regulatory network dynamics, and (iii) stem cell population renewal. The model demonstrates that stochastic epigenetic inheritance alone is sufficient to drive differentiation, de-differentiation, and transdifferentiation without external signals, providing a mechanistic foundation for the Waddington landscape concept. Predictions for the effects of histone methyltransferase inhibitors on reprogramming efficiency are consistent with experimental observations.

**Epigenetic Instability and Acquired Drug Resistance** (Wang, Lei, Zou, Jin, *PLoS Computational Biology*, 2025): Combining multi-omics data from PC9 lung cancer cells with a multiscale mathematical model, we revealed how epigenetic instability — fluctuations in chromatin state across cells — creates a pre-existing subpopulation of drug-tolerant persister (DTP) cells before therapy even begins. An evolutionary game theory framework showed that intermittent treatment exploits these dynamics to prevent DTP expansion. The model identifies optimal intermittent treatment windows, providing actionable guidance for clinical scheduling of EGFR inhibitors.

**Bivalent Domain Dynamics and Gene Expression Bistability** (Huang, Lei, *Journal of Theoretical Biology*, 2019): We modelled the positive feedback between H3K4me3 (active) and H3K27me3 (repressive) histone marks at bivalent promoters — a configuration common in stem cells — and showed that bistability in epigenetic state arises naturally from autocatalytic recruitment of chromatin-modifying complexes. This bistability is the molecular basis of cell-type memory and the barrier to spontaneous cell-fate change.

**Stochastic Methylation and Enhancer Heterogeneity** (Ye, Lei, *Journal of Theoretical Biology*, 2019): A stochastic model of CpG methylation dynamics at enhancers demonstrated how random methylation gains and losses during cell division generate the observed heterogeneity in enhancer activity across cells in a clonal population. The model quantitatively predicts the dependence of methylation heterogeneity on cell division rate, consistent with single-cell bisulfite sequencing data.

**Evolutionary Dynamics of Cancer and Epigenetic Regulation** (Lei, *Science China Mathematics*, 2020): A comprehensive review and modelling study connecting epigenetic regulation (cell-type transitions) to cancer evolution (clonal selection, treatment resistance), unifying the stem-cell and cancer-evolution frameworks into a coherent mathematical narrative.

---

## Implications for Cancer and Regenerative Medicine

This research direction has direct translational implications in two areas:

**Cancer drug resistance**: Epigenetic plasticity allows cancer cells to reversibly transition between drug-sensitive and drug-tolerant states, making *de novo* resistance not merely a genetic but an epigenetic phenomenon. Our models predict that treatment schedules must account for epigenetic dynamics — not just pharmacodynamics — to be optimally effective.

**Regenerative medicine and iPSC technology**: Understanding the quantitative barriers to cell-fate transitions enables the rational design of reprogramming protocols. Our models predict which combinations of transcription factors and epigenetic drugs maximise the efficiency of iPSC generation or direct transdifferentiation, reducing the current reliance on empirical trial-and-error.

---

## Selected Publications

- Huang R, Situ Q, Lei J\*. Dynamics of cell-type transition mediated by epigenetic modifications. *Journal of Theoretical Biology*, 2024, 577: 111664.
- Wang S, Lei J, Zou X, Jin S\*. Integrating multiscale mathematical modeling and multidimensional data reveals the effects of epigenetic instability on acquired drug resistance in cancer. *PLoS Computational Biology*, 2025, 21(2): e1012815.
- Lei J. Evolutionary dynamics of cancer: from epigenetic regulation to cell population dynamics. *Science China Mathematics*, 2020, 63(3): 411–424.
- Ye Y, Lei J\*. Stochastic methylation: A random process mediating enhancer methylation heterogeneity. *Journal of Theoretical Biology*, 2019, 481: 95–103.
