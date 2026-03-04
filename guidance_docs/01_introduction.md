# 01 · Introduction and Scope

[← Home](../README.md) | [Next: Biology of *V. cholerae* →](02_biology.md)

---

## 1.1 Purpose of This Document

This guidance document has been developed by the **PHA4GE (Public Health Alliance for Genomic Epidemiology) Cholera Genomics Working Group** to provide public health laboratories, clinicians, bioinformaticians, and surveillance professionals with a unified, evidence-based framework for the genomic analysis of *Vibrio cholerae*.

As genomic sequencing becomes increasingly accessible in low- and middle-income countries (LMICs) — where the burden of cholera is highest — it is imperative that standardised, reproducible, and ethically sound workflows accompany this technological expansion.

Cholera remains one of the most significant acute watery diarrheal (AWD) diseases globally, with the seventh pandemic still ongoing. Genomic surveillance offers unparalleled resolution for:

- Understanding transmission chains
- Detecting emerging antimicrobial resistance (AMR)
- Confirming outbreak origins
- Monitoring pandemic lineage evolution in near-real time

However, the power of genomic data is only realised when analyses are performed consistently, transparently, and with appropriate quality controls.

> **This document is a living resource.** As sequencing technologies, bioinformatics tools, and public health landscapes evolve, so too will this guidance. We welcome contributions from the global public health and genomics communities.

---

## 1.2 Scope

This document covers:

- The biology, epidemiology, and genomics of *V. cholerae* as foundational context
- The rationale for integrating bioinformatics into cholera surveillance
- Step-by-step guidance for genomic data analysis, from raw sequencing reads to actionable public health outputs
- Best practices for data sharing, interpretation, reporting, and ethical conduct

This document does **not** replace clinical guidelines for cholera case management or outbreak response. It is intended to complement — not substitute — existing WHO and national-level cholera control frameworks.

---

## 1.3 Target Audience

| Audience | Relevant Pages |
|----------|---------------|
| Public health professionals / epidemiologists | 01, 03, 05, 06, 17, 18, 19, 20 |
| Laboratory scientists / microbiologists | 07, 08, 09, 10, 11 |
| Bioinformaticians | 08–16 |
| Clinicians | 02, 03, 14, 17, 20 |
| Policy makers / health communicators | 01, 06, 18, 19, 20 |
| Students / new trainees | All pages, in order |

---

## 1.4 Learning Objectives

By working through this guidance document, users will be able to:

1. Describe the biology and global epidemiology of *Vibrio cholerae* and cholera.
2. Explain how whole-genome sequencing (WGS) enhances cholera surveillance beyond traditional methods.
3. Apply a quality-controlled workflow for bacterial genome assembly from ONT or Illumina sequencing data.
4. Characterise assembled genomes by lineage, MLST, virulence genes, and AMR profile.
5. Construct and interpret phylogenetic trees for outbreak investigation.
6. Share genomic data responsibly in accordance with FAIR principles and ethical standards.
7. Produce clear, actionable surveillance reports for public health decision-making.

---

## 1.5 How to Navigate This Document

Each of the 20 pages in this guidance covers a discrete topic and can be read in isolation. However, pages follow a logical workflow order and cross-reference each other throughout. New users are recommended to read in page order (01–20). Experienced users may jump directly to relevant sections.

**Navigation bar** at the top and bottom of each page provides links to the previous and next page, and back to the [Home index](../index.md).

---

## 1.6 Document Conventions

Throughout this document:

- `monospace text` is used for command-line commands, file names, and tool syntax
- **Bold text** indicates important terms on first use
- ⚠️ Warning boxes highlight common pitfalls or critical safety considerations
- ✅ Tip boxes highlight best practice recommendations
- Tables summarise key thresholds, tools, and decision frameworks

---

## 1.7 Citation

Please cite this document as:

> PHA4GE Cholera Genomics Working Group (2026). *Vibrio cholerae Genomic Surveillance: A PHA4GE Best Practices Guidance Document*, Version 1.0. https://pha4ge.org/cholera-guidance

---

## 1.8 Version History

| Version | Date | Notes |
|---------|------|-------|
| 1.0 | March 2026 | Initial release |

---

[← Home](../README.md) | [Next: Biology of *V. cholerae* →](02_biology.md)

*Licensed [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) · PHA4GE Bioinformatics Working Group*