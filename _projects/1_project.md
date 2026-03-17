---
layout: page
title: Mathematical Oncology and Cancer Immunotherapy
description: Multi-scale mathematical modeling and optimal control strategies for cancer immunotherapy, covering checkpoint inhibitors, CAR-T cell therapy, and combination treatment design.
img: assets/img/proj1.jpg
importance: 1
category: work
---

## Overview

Cancer immunotherapy has revolutionised oncology over the past decade, yet treatment responses remain highly heterogeneous across patients. Our research develops rigorous mathematical frameworks to decode the quantitative logic governing tumour–immune interactions, and to translate these insights into evidence-based, patient-specific treatment strategies.

We work at the interface of dynamical systems theory, optimal control, and clinical data integration. A central theme is the construction of **virtual patient cohorts** — computationally generated patient populations whose parameter distributions are calibrated to real clinical and genomic data (TCGA, clinical trials) — enabling *in silico* clinical trials that are impossible to run experimentally at scale.

---

## Key Research Questions

- What are the key determinants of treatment-free remission in chronic myeloid leukaemia (CML) after tyrosine kinase inhibitor (TKI) discontinuation?
- How can we design mathematically optimal adaptive therapy schedules that exploit tumour evolutionary dynamics rather than fighting them?
- What combination immunotherapy regimens most effectively convert immunologically "cold" tumours to "hot" ones?
- How do tumour heterogeneity and immune escape jointly constrain the efficacy of checkpoint inhibitors and CAR-T cell therapies?

---

## Modelling Approach

Our models typically couple:

1. **Tumour cell compartments** — sensitive cells, resistant cells, and phenotypically plastic subpopulations, governed by ordinary or delay differential equations.
2. **Immune effector dynamics** — cytotoxic T lymphocytes (CTL), regulatory T cells (Treg), natural killer cells, dendritic cells, and key cytokines (IFN-γ, IL-10, TGF-β), modelled as interacting ODE systems.
3. **Treatment dynamics** — pharmacokinetic/pharmacodynamic descriptions of immune checkpoint inhibitors (anti-PD-1, anti-PD-L1, anti-CTLA-4), CAR-T cell infusions, cancer vaccines, and small-molecule targeted agents.

Parameter estimation relies on **Markov Chain Monte Carlo (MCMC)** and **Approximate Bayesian Computation (ABC)** to fit models to individual patient trajectories, generating heterogeneous virtual populations that recapitulate observed clinical variability. Treatment optimisation is then carried out using **Pontryagin's Maximum Principle (PMP)**, **bilevel optimisation**, or **model predictive control**, seeking schedules that maximise tumour eradication while minimising toxicity and the risk of resistance emergence.

---

## Representative Results

**Treatment-Free Remission in CML** (Lai, Jiao, Zhang, Lei, *npj Systems Biology and Applications*, 2024): Through computational modelling and parameter sensitivity analysis, we identified the key immunological determinants — CTL effector strength, leukemic stem cell dynamics, and TKI-mediated immunomodulation — that predict which patients will achieve durable treatment-free remission (TFR) after stopping imatinib. This work provides a quantitative framework to guide the timing of TKI discontinuation in clinical practice.

**Adaptive Therapy for Prostate Cancer** (Wang, Lei, *Journal of Mathematical Biology*, 2025): We formulated a novel bilevel optimisation problem embedding tumour evolutionary dynamics within the treatment scheduling layer. Applied to metastatic castrate-resistant prostate cancer (mCRPC), the model demonstrates that adaptive therapy — dynamically modulating androgen deprivation based on tumour burden — substantially delays resistance compared to continuous maximal-dose therapy.

**PD-L1 Heterogeneity and Adaptive Immunotherapy** (Ma, Lei, Lai, *Journal of Mathematical Biology*, 2023): Integrating TCGA epigenomic data, we modelled the dynamic evolution of intra-tumoral PD-L1 expression heterogeneity. Virtual patient simulations show that adaptive dosing strategies keyed to real-time PD-L1 status outperform conventional maximum tolerated dose protocols, offering a rationale for biomarker-driven dose adaptation.

**CAR-T Cell Therapy Optimisation** (Li, Lei, *Mathematical Biosciences and Engineering*, 2025): A mathematical model of CAR-T cell dynamics in B-cell acute lymphoblastic leukaemia (B-ALL) was used to identify optimal CAR-T subtype compositions and infusion schedules that prevent CAR-T exhaustion while sustaining anti-tumour efficacy.

**Combination Immunotherapy — Colorectal Cancer** (Li, Zhang, Lai, Lei, *Mathematical Biosciences*, 2026): A multiscale model integrating tumour cell dynamics, immune cell interactions, and cytokine networks was calibrated to clinical data via ABC. The ratio of CTL to Treg at treatment initiation emerged as a robust predictive biomarker for anti-PD-L1 plus vaccine combination therapy.

**Breast Cancer Combination Regimen Optimisation** (Xiong, Xia, Xue, Lei, *Bulletin of Mathematical Biology*, 2025): Optimal control analysis of mRNA cancer vaccine combined with anti-CTLA-4 identified administration schedules that maximise tumour suppression while respecting toxicity constraints, demonstrating the power of mathematical optimisation to navigate the high-dimensional space of combination regimen design.

---

## Broader Impact

This research programme directly addresses the clinical challenge of **precision oncology**: moving from population-average treatment protocols towards patient-specific strategies informed by measurable biomarkers and mathematical predictions. By creating a rigorous quantitative link between tumour biology, immune dynamics, and treatment outcomes, our models serve as *in silico* test beds for treatment hypotheses that would be infeasible, unethical, or prohibitively expensive to test in the clinic.

---

## Selected Publications

- Lai X, Jiao X, Zhang H, Lei J\*. Computational modeling reveals key factors driving treatment-free remission in chronic myeloid leukemia patients. *npj Systems Biology and Applications*, 2024, 10: 45.
- Wang D, Lei J\*. Optimal adaptive therapeutic schedules for metastatic castrate-resistant prostate cancer based on bilevel optimization problem. *Journal of Mathematical Biology*, 2025, 90(6): 60.
- Li C, Wei Y, Lei J\*. Quantitative cancer-immunity cycle modeling for predicting disease progression in advanced metastatic colorectal cancer. *npj Systems Biology and Applications*, 2025, 11(1): 33.
- Li R, Lei J\*. Optimal therapy schedule of chimeric antigen receptor (CAR) T cell immunotherapy. *Mathematical Biosciences and Engineering*, 2025, 22(7): 1653–1679.
- Ma S, Lei J, Lai X. Modeling tumour heterogeneity of PD-L1 expression in tumour progression and adaptive therapy. *Journal of Mathematical Biology*, 2023, 86(3): 38.
- Li C, Ren Z, Yang G, Lei J\*. Mathematical modelling of tumor immune interactions: the role of anti-FGFR and anti-PD-1 in the combination therapy. *Bulletin of Mathematical Biology*, 2024, 86(9): 116.
- Xiong Z, Xia Y, Xue L, Lei J\*. Mathematical modelling and optimization of medication regimens for combination immunotherapy of breast cancer. *Bulletin of Mathematical Biology*, 2025, 87(7): 88.
- Li C, Zhang H, Lai X, Lei J\*. Combination therapy for colorectal cancer with anti-PD-L1 and cancer vaccine: A multiscale mathematical model of tumor-immune interactions. *Mathematical Biosciences*, 2026, 394: 109637.
- Zhang H, Lei J, Lai X\*. Treatment of melanoma with dendritic cell vaccines and immune checkpoint inhibitors: A mathematical modeling study. *Journal of Theoretical Biology*, 2023, 568: 111489.
