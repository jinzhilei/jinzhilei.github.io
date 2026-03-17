---
layout: page
title: Infectious Disease Modelling and Epidemic Dynamics
description: Mathematical models of COVID-19 transmission at multiple scales — from within-host viral dynamics to population-level spread — informing public health interventions including contact tracing, quarantine strategies, and non-pharmaceutical interventions.
img: assets/img/proj4.jpg
importance: 4
category: work
---

## Overview

The COVID-19 pandemic presented an unprecedented challenge that required rapid, rigorous mathematical modelling at multiple scales simultaneously: understanding how the virus replicates within individual patients, how it spreads through populations under different contact patterns, and how public health interventions can most effectively suppress transmission. Our group responded with a focused programme of epidemic modelling research during 2021–2023, producing a set of interlocking papers that addressed these questions from within-host dynamics to city-level control policy.

A distinguishing feature of our approach was the integration of **multi-scale modelling** (coupling within-host and between-host dynamics), **individual-based simulation** (allowing heterogeneous contact networks and stochastic transmission), and **data-driven calibration** (fitting models to observed case counts across multiple real-world settings) — all applied simultaneously to the same epidemic system.

---

## Research Questions

- What within-host mechanisms drive the transition from mild to severe COVID-19, and how do different antiviral strategies modulate this progression?
- How much does under-detection of asymptomatic cases distort our understanding of epidemic size and trajectory?
- Which combinations of non-pharmaceutical interventions (NPIs) are most effective at eliminating local transmission, and what is the minimum necessary intervention?
- Can contact-tracing-driven quarantine, implemented with realistic delays and coverage, suppress epidemic spread without requiring blanket lockdowns?

---

## Multi-Scale Model of SARS-CoV-2 Infection

**Data-Driven Multi-Scale Mathematical Modelling of SARS-CoV-2 Infection** (Wang, Hao, Pan, Lei, Zou, *PLoS Computational Biology*, 2021): This flagship study constructed a three-layer multi-scale model:

1. **Within-cell layer**: viral RNA replication kinetics, interferon signalling, and innate immune activation in individual epithelial cells.
2. **Multi-cell layer**: spatial spread of infection across the respiratory epithelium, mediated by cell-to-cell viral transmission and local immune responses.
3. **Systemic immune layer**: T cell and antibody dynamics, including the threshold at which T cell exhaustion shifts clinical outcome from mild to severe disease.

The model was calibrated to longitudinal clinical data from COVID-19 patients with a range of disease severities. A key finding was the identification of **T cell exhaustion kinetics** as the critical bifurcation point separating mild and severe outcomes — a mechanistic explanation for why some patients deteriorate rapidly while others recover. The model quantitatively evaluated the efficacy of remdesivir, hydroxychloroquine, and interferon therapy, predicting differential outcomes consistent with clinical trial results.

---

## Population-Level Transmission and Under-Detection

**Impact of Insufficient Detection in COVID-19 Outbreaks** (Deng, Xing, Zhu, Lei, *Mathematical Biosciences and Engineering*, 2021): We extended the standard SEIR compartmental framework to incorporate a stochastic Poisson detection process — explicitly modelling the probability that an infected individual (especially asymptomatic) is identified and reported. Applied to outbreak data from Guam, Texas, and other regions, the model quantified the systematic underestimation of true case counts under different testing rates. The work provided actionable estimates of the "true" epidemic size, a quantity critical for assessing herd immunity and planning healthcare capacity.

---

## Non-Pharmaceutical Interventions: Individual-Based Analysis

**Effectiveness of Non-Pharmaceutical Interventions Against Local Transmission of COVID-19** (Xu, Pei, Liu, Lei, *Infectious Disease Modelling*, 2021): Using an individual-based model (IBM) with realistic household and community contact networks, we systematically evaluated the effectiveness of masks, self-isolation of symptomatic cases, social distancing, and quarantine of first- and second-degree contacts. The central finding was that **quarantine of second-degree contacts** (contacts of confirmed cases' contacts) was the decisive intervention for eliminating local transmission chains — without this measure, other NPIs alone were insufficient. This conclusion directly informed national contact-tracing policy discussions during the "dynamic zero-COVID" period in China.

---

## Contact-Tracing-Driven Quarantine

**Modelling COVID-19 Epidemic with Confirmed-Cases-Driven Contact Tracing Quarantine** (Wu, Liang, Lei, *Infectious Disease Modelling*, 2023): We developed a delayed differential equation system where the quarantine rate is a function of current daily confirmed case counts — capturing the real-world operational constraint that tracing capacity is triggered by and scales with confirmed cases. Counter-intuitively, simulations showed that extending quarantine duration from 7 to 21 days had limited additional benefit, whereas contact tracing without concurrent contact reduction was insufficient to eliminate epidemics. These findings clarified the relative importance of reducing contact rates versus extending quarantine duration, a policy-relevant distinction during the transition away from strict containment.

---

## Impact and Policy Relevance

Collectively, this research programme made methodological contributions (multi-scale coupling, confirmed-case-driven quarantine models) and provided direct policy-relevant quantitative estimates at a time when such analysis was urgently needed. The individual-based modelling work, in particular, provided the first rigorous quantitative justification for second-degree contact quarantine as a critical control measure in the Chinese epidemic response.

---

## Selected Publications

- Wang S, Hao M, Pan Z, Lei J, Zou X\*. Data-driven multi-scale mathematical modeling of SARS-CoV-2 infection reveals heterogeneity among COVID-19 patients. *PLoS Computational Biology*, 2021, 17(11): e1009587.
- Xu C, Pei Y, Liu S, Lei J\*. Effectiveness of non-pharmaceutical interventions against local transmission of COVID-19: an individual-based modelling study. *Infectious Disease Modelling*, 2021, 6: 848–858.
- Deng Y, Xing S, Zhu M, Lei J\*. Impact of insufficient detection in COVID-19 outbreaks. *Mathematical Biosciences and Engineering*, 2021, 18(6): 9727–9742.
- Wu F, Liang X, Lei J\*. Modelling COVID-19 epidemic with confirmed cases-driven contact tracing quarantine. *Infectious Disease Modelling*, 2023, 8(2): 415–426.
