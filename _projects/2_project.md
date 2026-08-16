---
layout: page
title: Causal Inference & Mendelian Randomization
description: Recovering effects of latent exposures by integrating GWAS summary data across multiple biomarkers.
permalink: /projects/mendelian-randomization/
importance: 2
category: research
github: https://github.com/Jin93/MRLE
related_publications: false
---

Mendelian randomization (MR) uses genetic variants as instrumental variables to estimate the
causal effect of an exposure on an outcome. Many exposures of interest, however, are **latent**
or difficult to measure directly. My work develops MR methods that recover the effect of an
underlying common exposure by integrating GWAS summary statistics across multiple observed
biomarkers, improving statistical power and robustness over single-biomarker approaches.

#### Methods

**MRLE** (Mendelian Randomization analysis for a Latent Exposure) leverages GWAS summary-level
information on multiple biomarkers that share an underlying common exposure, enabling causal
analysis when the exposure itself is unmeasured.

**CaLMR** (Causal analysis of Latent exposures using Mendelian Randomization) extends this to a
Bayesian framework for latent exposures, using GWAS summary statistics for traits co-regulated
by the exposures.

#### Software & resources

- MRLE — <https://github.com/Jin93/MRLE>
- CaLMR — <https://github.com/yueuuy/CaLMR>

#### Key publications

- *Mendelian randomization analysis using multiple biomarkers of an underlying common exposure.* Biostatistics, 2024. [[Paper]](https://academic.oup.com/biostatistics/article/25/4/1015/7624600)
- *Bayesian Mendelian Randomization Analysis for Latent Exposures Leveraging GWAS Summary Statistics for Traits Co-Regulated by the Exposures.* medRxiv, 2024. [[Preprint]](https://www.medrxiv.org/content/10.1101/2024.11.25.24317939v1)
