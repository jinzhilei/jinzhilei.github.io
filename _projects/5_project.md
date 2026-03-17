---
layout: page
title: Gene Regulatory Networks, Developmental Patterning, and Single-Cell Genomics
description: Mathematical modelling of gene network dynamics from Drosophila imaginal disc patterning to morphogen gradient robustness; quantitative single-cell RNA sequencing analysis including stemness scoring and AI-driven data generation.
img: assets/img/proj5.jpg
importance: 5
category: work
---

## Overview

Gene regulatory networks (GRNs) are the molecular circuits that orchestrate development, maintain cell identity, and coordinate responses to signals. Our group studies GRN dynamics using tools from nonlinear dynamical systems theory, stochastic processes, and — increasingly — machine learning and single-cell genomics. This research direction spans from classical problems in developmental biology (pattern formation, morphogen gradients) to cutting-edge computational single-cell analysis (stemness quantification, generative modelling of single-cell RNA sequencing data).

A unifying theme is the question of **robustness versus variability**: how do biological networks reliably produce precise developmental outcomes (robustness) while simultaneously maintaining the cell-to-cell variability (heterogeneity) that is necessary for tissue homeostasis, adaptation, and, in pathological contexts, tumour evolution?

---

## Research Directions

### 1. Drosophila Imaginal Disc Patterning and Morphogen Gradients

The Drosophila wing imaginal disc is a classical model system for studying how positional information — encoded in morphogen concentration gradients — is converted into discrete, sharply bounded gene expression domains. Our early work (supported by the NSFC Young Scientist Fund, 2007–2009) used mathematical modelling to investigate:

- How morphogen gradients achieve robust positional encoding despite variability in ligand production, diffusion, and receptor binding
- The role of feedback regulation (extracellular modulators such as Dally, Pentagone) in scaling the gradient with tissue size during growth
- The dynamical properties of the transcription factor cascade downstream of Dpp/BMP signalling (Mad, Brk, Sal, Omb)

**Morphogen Dynamics and Growth Control** (Lei, *Applied Mathematics and Systems Analysis*, 2016): A comprehensive review and modelling study of the mathematical principles underlying morphogen gradient formation, robustness mechanisms (self-enhanced degradation, modulator feedback), and the coupling between morphogen signalling and tissue growth control — a connection relevant not only to development but also to tumour growth.

**Robustness of Dpp Signalling Gradients in the Drosophila Wing Disc** (Lei, Bhatt, Bhatt, Bhatt, *DCDS-B*, 2011): A mathematical analysis of how the extracellular modulators of Dpp signalling create a gradient with properties (robustness to production rate variation, scaling with disc size) consistent with measured *in vivo* data.

### 2. Gene Network Topology, Bistability, and Developmental Switches

Gene regulatory networks that mediate cell-fate decisions often contain positive feedback loops that create bistability — two stable steady states separated by an unstable threshold. Our group has investigated:

- The conditions under which specific network motifs (mutual repression, autoactivation, feedforward loops) generate bistable or oscillatory dynamics
- How bivalent chromatin domains (co-occurring H3K4me3 and H3K27me3 marks) create bistability at individual gene loci, and how this connects to the multi-stability of cell-type identity
- The mathematical relationship between network topology and the accessibility of different attractors in the epigenetic landscape

**Positive Feedback Dynamics at Bivalent Gene Loci** (Huang, Lei, *Journal of Theoretical Biology*, 2018): A stochastic model of histone modification dynamics at bivalent domains showed that autocatalytic recruitment of Polycomb and Trithorax complexes creates bistable on/off switching at developmental gene loci, explaining the kinetics of gene activation during cell-fate transitions.

**Individual Entropy as a Macroscopic Variable for Gene Regulatory Networks** (Liu, Hao, Lei, *International Journal of Modern Physics B*, 2021): We defined the "individual entropy" — the Shannon entropy of a single cell's gene expression state relative to a reference distribution — as a scalar summary of GRN state. This quantity serves as an early warning signal for critical transitions (cell-fate changes, cancer initiation), and is computable from single-cell RNA sequencing data, bridging theoretical dynamical systems analysis with genomics data.

### 3. Stemness Quantification from Single-Cell RNA Sequencing

Stem cells and cancer stem cells share key transcriptional signatures, yet identifying these signatures robustly from single-cell RNA sequencing (scRNA-seq) data is challenging due to high dimensionality, sparsity, and technical noise.

**Quantitative Modelling of Stemness in Single-Cell RNA Sequencing Data** (Jiang, Liu, Song, Lei, *Journal of Computational Biology*, 2024): We developed a nonlinear one-class support vector machine (OC-SVM) method to quantify a continuous "stemness score" for each cell in a scRNA-seq dataset, trained on curated reference stem cell transcriptomes. Applied to cancer datasets, the method identifies stem-like tumour subpopulations that are enriched for drug resistance and metastatic potential. The nonlinear kernel substantially outperforms linear approaches and previous entropy-based stemness scores in cross-dataset benchmarking.

### 4. Generative AI Models for Single-Cell Genomics

Single-cell sequencing data generation for downstream analysis, privacy-preserving data sharing, and augmentation of rare cell type datasets requires high-fidelity generative models. We are at the frontier of applying deep generative modelling to scRNA-seq data.

**scRDiT: Generating Single-Cell RNA-seq Data by Diffusion Transformers** (Dong, Cui, Liu, Lei, *Interdisciplinary Sciences: Computational Life Sciences*, 2026): We proposed scRDiT, a generative framework based on the **Diffusion Transformer (DiT)** architecture, adapted for the count-data structure and high sparsity of scRNA-seq. The model achieves state-of-the-art generation fidelity as measured by standard scRNA-seq benchmarks, while introducing a novel sampling acceleration scheme that reduces inference time by an order of magnitude. scRDiT opens avenues for synthetic data augmentation in rare disease research, federated learning across hospitals, and in-silico perturbation studies.

### 5. Systems Biology: A Graduate-Level Mathematical Modelling Framework

Alongside primary research, a significant contribution of our group is the synthesis and transmission of mathematical systems biology knowledge. **Systems Biology** (Lei, Springer, 2021) — published in the *Lecture Notes on Mathematical Modelling in the Life Sciences* series — provides a rigorous mathematical introduction to continuous and stochastic dynamical systems, gene regulatory networks, stem cell regeneration, and cancer evolution, aimed at graduate students in applied mathematics and computational biology. This textbook has been used in courses at several Chinese universities and internationally.

---

## Selected Publications

- Jiang H, Liu JX, Song Y, Lei J\*. Quantitative modeling of stemness in single-cell RNA sequencing data: a nonlinear one-class support vector machine method. *Journal of Computational Biology*, 2024, 31(1): 41–57.
- Dong S, Cui Z, Liu D, Lei J\*. scRDiT: Generating single-cell RNA-seq data by diffusion transformers and accelerating sampling. *Interdisciplinary Sciences: Computational Life Sciences*, 2026, 18(1): 314–325.
- Liu C, Hao L, Lei J\*. Macroscopic dynamics of gene regulatory networks revealed by individual entropy. *International Journal of Modern Physics B*, 2021.
- Lei J. Systems Biology. Springer, 2021. (*Lecture Notes on Mathematical Modelling in the Life Sciences*). DOI: 10.1007/978-3-030-73033-8.
- Lei J\*. Mathematical models of morphogen dynamics and growth control. *Annals of Mathematical Sciences and Applications*, 2016, 1(2): 427–471.
- Lei J, Bhatt DL\*, et al. Robustness of morphogen gradients with "bucket brigade" transport through membrane-associated non-receptors. *Discrete and Continuous Dynamical Systems – Series B*, 2011, 16(3): 831–860.
