---
layout: page
title: Health Equity in Polygenic Risk Prediction
description: Bayesian and ensemble methods for accurate, equitable disease risk prediction across ancestry groups.
permalink: /projects/prs-health-equity/
img: assets/img/PennPRS.jpeg
importance: 1
category: research
github: https://github.com/PennPRS/Pipeline
related_publications: false
---

Polygenic risk scores (PRS) summarize an individual's inherited susceptibility to disease,
but models trained predominantly in European-ancestry cohorts transfer poorly to other
populations — widening, rather than narrowing, health disparities. A central goal of my
research is to make polygenic risk prediction both **accurate** and **equitable** across
diverse ancestry groups, and to deliver these methods as usable, scalable software.

#### Methods

**MUSSEL** (MUltivariate Spike-and-Slab and Ensemble Learning) is a Bayesian framework that
jointly models effect sizes across multiple ancestry groups, borrowing information across
populations while respecting population-specific genetic architecture. It integrates GWAS
summary statistics with external LD reference data to produce enhanced ancestry-specific PRS.

**PennPRS** is a centralized cloud-computing platform that makes state-of-the-art PRS model
training accessible without specialized computing infrastructure, supporting both single- and
multi-ancestry methods through an online interface and an offline pipeline for large-scale
analyses.

#### Software & resources

- PennPRS platform — <https://pennprs.org/>
- PennPRS offline pipeline — <https://github.com/PennPRS/Pipeline>
- MUSSEL — <https://github.com/Jin93/MUSSEL>

#### Key publications

- *PennPRS: a centralized cloud computing platform for efficient polygenic risk score training in precision medicine.* medRxiv, 2025. [[Preprint]](https://www.medrxiv.org/content/10.1101/2025.02.07.25321875v1)
- *MUSSEL: Enhanced Bayesian polygenic risk prediction leveraging information across multiple ancestry groups.* Cell Genomics, 2024. [[Paper]](https://www.cell.com/cell-genomics/fulltext/S2666-979X(24)00095-8)

<br />
This direction is supported by my NIH Pathway to Independence Award (K99/R00) from NHGRI.
