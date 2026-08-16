---
layout: page
permalink: /research/
title: Research
description: Statistical and computational methods for integrating large-scale, multi-source data in public health and medicine.
nav: false
nav_order: 2
---

My research program develops statistical and computational methods that integrate
large-scale, multi-source datasets to address problems in public health and medicine,
with an emphasis on **health equity**, **statistical genetics**, and **scalable,
open-source software**. The work spans methods development, large-scale data analysis,
and the release of tools that the broader research community can use directly.

---

#### [**Health equity in disease risk prediction**]({{ '/projects/prs-health-equity/' | relative_url }})

A central theme of my work is making polygenic risk prediction accurate and equitable
across diverse ancestry groups, where methods trained primarily in European-ancestry
cohorts often underperform. I develop Bayesian and ensemble-learning methods that borrow
information across populations to improve ancestry-specific polygenic risk scores (PRS),
and I build platforms that make these methods usable at scale.

- **MUSSEL** — Enhanced Bayesian polygenic risk prediction leveraging information across
  multiple ancestry groups. *Cell Genomics*, 2024. [[Paper]](https://www.cell.com/cell-genomics/fulltext/S2666-979X(24)00095-8) [[Code]](https://github.com/Jin93/MUSSEL)
- **PennPRS** — A centralized cloud-computing platform for efficient PRS model training in
  precision medicine. *medRxiv*, 2025. [[Preprint]](https://www.medrxiv.org/content/10.1101/2025.02.07.25321875v1) [[Platform]](https://pennprs.org/)

#### [**Causal inference and Mendelian randomization**]({{ '/projects/mendelian-randomization/' | relative_url }})

I develop Mendelian randomization (MR) methods that recover the effects of latent or
hard-to-measure exposures by integrating GWAS summary statistics across multiple observed
biomarkers, improving power and robustness over single-biomarker approaches.

- **MRLE** — Mendelian randomization analysis using multiple biomarkers of an underlying
  common exposure. *Biostatistics*, 2024. [[Paper]](https://academic.oup.com/biostatistics/article/25/4/1015/7624600) [[Code]](https://github.com/Jin93/MRLE)
- **CaLMR** — Bayesian MR analysis for latent exposures leveraging GWAS summary statistics
  for co-regulated traits. *medRxiv*, 2024. [[Preprint]](https://www.medrxiv.org/content/10.1101/2024.11.25.24317939v1) [[Code]](https://github.com/yueuuy/CaLMR)

#### [**High-dimensional and graph-informed inference**]({{ '/projects/high-dimensional-inference/' | relative_url }})

I build methods for high-dimensional, complex-structured data that incorporate known
biological structure — such as gene networks — to improve the detection of disease-associated
signals.

- **T2-DAG** — A powerful test for differentially expressed gene pathways via graph-informed
  structural equation modeling. *Bioinformatics*, 2022. [[Paper]](https://academic.oup.com/bioinformatics/article/38/4/1005/6424893) [[Code]](https://github.com/Jin93/T2DAG)

#### [**Risk prediction for population and public health**]({{ '/projects/population-health-risk/' | relative_url }})

I apply statistical modeling to translate large-scale data into individual- and
community-level risk assessments that inform public-health decision making.

- Individual and community-level risk for COVID-19 mortality in the United States.
  *Nature Medicine*, 2021. [[Paper]](https://www.nature.com/articles/s41591-020-01191-8)

---

#### **Funding**

My research is supported by an **NIH Pathway to Independence Award (K99/R00)** from the
National Human Genome Research Institute ([NHGRI](https://www.genome.gov/)), for which I
serve as Principal Investigator, developing methods for multi-ancestry disease risk
prediction that integrate genetic and non-genetic risk factors across data sources.
[[NIH RePORTER]](https://reporter.nih.gov/search/5u7x8jpqxUSznDKcHnIqSw/project-details/10349828)

<br />

For a full list of publications, see the [Publications]({{ '/publications/' | relative_url }})
page; software and platforms are available on the [Software]({{ '/software/' | relative_url }})
page.
