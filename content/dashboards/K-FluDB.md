---
title: K-FluDB
date: 2026-05-12T12:12:00
banner: /images/Screenshot from 2026-05-12 12-11-30.png
description: Explore genomic and epidemiological surveillance data of SARS-CoV-2 in Mexico. This dashboard provides weekly updates on variant circulation, transmission dynamics, and outbreak trends, combining sequencing and case data to support national surveillance and public health response.
type: internal
draft: false
menu:
  dashboards:
    name: K-FluDB
    identifier: K-FluDB_dashboard
    weight: 1
dashboards_topics:
  - Influenza
  - viruses
---

K-FluDB is a high-performance k-mer database that optimizes Influenza A surveillance by compressing genomic data by 99.64%. By eliminating redundancy across 50 subtype combinations, it achieves >99% accuracy in subtype identification and provides critical insights into viral reassortment and evolution for proactive public health response.

You can read the published article here: [K-FluDB](https://academic.oup.com/bioinformaticsadvances/advance-article/doi/10.1093/bioadv/vbaf254/8280401)

Any input sequences can be used with this algorithm to generate a compressed version of the data, enabling enhanced subtype-specific or species-specific annotation via a Bowtie2 index. Custom iterations of this pipeline can be adapted for any data type, including sequences from partner pathogen nodes such as [Netherlands Arboviruses](https://www.pathogensportal.nl/sequences.html), [Norway Databases](https://www.pathogens.no/rdm/databases), [Spanish Pathogens Portal (RELECOV 2.0)](https://pathogensportal.isciii.es/), [Sweden (SLU)](https://www.pathogens.se/dashboards/influenza_quantification/) and [Swiss Pathogens Portal](https://pathogensportal.ch/).

Availability and implementation
Three versions of K-FluDB, optimized for read lengths of 75, 150, and 300 nucleotides, are freely available at https://zenodo.org/records/17203072, and the source code is available at https://github.com/usjunco/pange
