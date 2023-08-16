---
title: "HEGSRR Template v1.0 Release"
categories:
  - blog
tags:
  - Template
  - Reproducibility
  - Preregistration
  - GitHub
  - Compendium
---

We are pleased to announce the [v1.0 release](https://github.com/HEGSRR/HEGSRR-Template/tree/v1.0) of our [Github template](https://github.com/HEGSRR/HEGSRR-Template) for doing reproducible research in HEGS!
This version of the template integrates lessons learned from our experience from two years of doing reproduction studies, replication studies, and original research in the human-environment and geographical sciences.
Our experience includes mentoring and teaching graduate and undergraduate students, working in research teams, and reformatting other researchers' data and code to conform to our template.
This release conforms more tightly to international metadata standards for projects ([Dublin Core](https://www.dublincore.org/specifications/dublin-core/dces/)) and geographic data ([ISO 191* series](https://www.iso.org/standard/26020.html)), and is easily integrated with [OSF](https://osf.io) projects and registrations.

This release of the HEGSRR Template contains the following updates:
- template for project metadata in the main readme file
- markdown template for data metadata in the data/metadata directory
- changed the name of tables indexing data, metadata, and procedures from `*_metadata.csv` to `*_index.csv` and simplified the tables to avoid duplication with metadata documents
- revised and simplified template analysis plan in three formats: markdown, Rmarkdown, and Jupyter Python notebook
- additional code and guidance in R and Python for setting up, documenting, and reproducing computational environments

Our most recent reproduction study of [Spielman et al 2020's Evaluation of the Social Vulnerability Index](Evaluation of the Social Vulnerability Index) implements this new version of the template.
Compare the legibility of our reproduction research compendium to the [original study's GitHub repository](https://github.com/geoss/sovi-validity).
The original repository was remarkably complete for a geographic information science research paper, but still left [plenty of work to be done](https://doi.org/10.17605/OSF.IO/4S62B).
