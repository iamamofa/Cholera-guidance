# Vibrio cholerae Genomic Surveillance
## A PHA4GE Best Practices Guidance Document

![PHA4GE Logo](phage.png)

**Version:** 1.0 | **Published:** March 2026 | **License:** [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

> **Working Group:** PHA4GE Pipelines and Visualization Group  
> **How to cite:** PHA4GE Pipelines and Visualization Group (2026). *Vibrio cholerae Genomic Surveillance: A PHA4GE Best Practices Guidance Document*.
 https://pha4ge.org/cholera-guidance

---

## Overview

According to the World Health Organisation (WHO), outbreaks of acute watery diarrhea (AWD)-related diseases are likely to occur unless surveillance systems are in place to rapidly detect their associated pathogens and respond accordingly. These materials provide a unified, evidence-based framework for the genomic analysis of *Vibrio cholerae*, covering the full workflow from raw sequencing data to actionable public health outputs.

Cholera remains one of the most significant infectious disease threats globally, with the seventh pandemic still ongoing. Genomic surveillance offers unparalleled resolution for understanding transmission chains, detecting emerging antimicrobial resistance (AMR), and monitoring pandemic lineage evolution in near-real time.

---

## Guidance Documents

| # | Page | Description |
|---|------|-------------|
| 01 | [Introduction & Scope](guidance_docs/01_introduction.md) | Purpose, target audience, scope and how to use this document |
| 02 | [Biology of *Vibrio cholerae*](guidance_docs/02_biology.md) | Taxonomy, morphology, virulence mechanisms, ecology |
| 03 | [Epidemiology of Cholera](guidance_docs/03_epidemiology.md) | Global burden, geographic distribution, transmission dynamics |
| 04 | [Genomics of *V. cholerae*](guidance_docs/04_genomics.md) | Genome architecture, key genomic elements, pandemic lineage |
| 05 | [Why Bioinformatics Is Essential](guidance_docs/05_why_Bio.md) | Limitations of traditional methods, what WGS enables |
| 06 | [Why PHA4GE Needs to Lead](guidance_docs/06_why_PHA4GE.md) | Standards, best practices, community coordination |
| 07 | [Laboratory Prerequisites & Sequencing](guidance_docs/07_lab_prequisite.md) | Biosafety, isolation, DNA extraction, sequencing platforms |
| 08 | [Data Management & File Formats](guidance_docs/08_data_management.md) | File formats, naming, version control, storage |
| 09 | [Sequence Quality Control](guidance_docs/09_sequence_QC.md) | FastQC, trimming, host depletion, contamination screening |
| 10 | [Genome Assembly](guidance_docs/10_genome_assembly.md) | De novo, reference-based, hybrid assembly workflows |
| 11 | [Assembly Quality Assessment](guidance_docs/11_assembly_QA.md) | QUAST, CheckM, quality tiers, pass/fail criteria |
| 12 | [Strain Typing & Lineage Classification](guidance_docs/12_strain_typing_Lineage.md) | MLST, cgMLST, pandemic wave assignment, Vibriowatch |
| 13 | [Phylogenetic Analysis](guidance_docs/13_phylogenetic_Analysis.md) | SNP calling, Gubbins, IQ-TREE2, Microreact, molecular clocks |
| 14 | [Antimicrobial Resistance Detection](guidance_docs/14_AMR.md) | AMR genes, point mutations, quality thresholds |
| 15 | [Virulence Gene Prediction](guidance_docs/15_Virulence_Gene_prediction.md) | ctxB allele typing, TCP, VPI islands, VirulenceFinder |
| 16 | [Plasmid Detection & Analysis](guidance_docs/16_Plasmid_Detection.md) | MOB-suite, PlasmidFinder, Chr2 pitfalls |
| 17 | [Interpretation of Results](guidance_docs/17_Interpretation.md) | Integration framework, SNP thresholds, common pitfalls |
| 18 | [Data Sharing & FAIR Principles](guidance_docs/18_Data_sharing_FAIRS.md) | Repositories, metadata standards, data sovereignty |
| 19 | [Ethics, Governance & Responsible Use](guidance_docs/19_Ethics_governance_Res.md) | Patient privacy, equitable collaboration, DURC |
| 20 | [Reporting & Communication](guidance_docs/20_Reporting_and_communication.md) | Rapid reports, full reports, IHR obligations |

---

## Case Studies

- [**Haiti 2022**](case_studies/01-haiti.md) — Resurgence of cholera after apparent elimination; imported wave 3 strain
- [**Zimbabwe 2018**](case_studies/02-zimbabwe.md) — Multi-drug resistant O1 El Tor outbreak with SXT ICE characterisation
- [**Yemen 2016–present**](case_studies/03-yemen.md) — Largest recorded cholera outbreak in history; conflict-driven transmission

---

## Contributing

This document is a **living resource**. Contributions are welcomed from the global public health and genomics communities.

1. Open a [GitHub Issue](#) to propose changes
2. Submit a [Pull Request](#) with modifications
3. Join the Pipeines and Visualization Working Group at [pha4ge.org](https://pha4ge.org)

---
## Current guidance documents 
- [Surveillance Strategies](https://github.com/pha4ge/wastewater-guidance/blob/main/guidance_docs/SurveillanceStrategies-GuidanceDoc.md)
- [Data Analysis](https://github.com/pha4ge/wastewater-guidance/blob/main/guidance_docs/DataAnalysis-GuidanceDoc.md)
- [Data Sharing](https://github.com/pha4ge/wastewater-guidance/blob/main/guidance_docs/DataSharing-GuidanceDoc.md)
- [Ethics and Legality](https://github.com/pha4ge/wastewater-guidance/blob/main/guidance_docs/EthicsAndLegality-GuidanceDoc.md)

---

## Quick Links

- [PHA4GE](https://pha4ge.org)
- [Vibriowatch / PathogenWatch](https://pathogen.watch/collections/vibriowatch)
- [WHO Cholera Fact Sheet](https://www.who.int/news-room/fact-sheets/detail/cholera)
- [GTFCC Roadmap to 2030](https://www.gtfcc.org)
- [NCBI SRA](https://www.ncbi.nlm.nih.gov/sra)
- [CholeraBook](https://vibriowatch.readthedocs.io)

---


*Licensed [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) · Built by the PHA4GE Pipelines and Visualization Working Group*

