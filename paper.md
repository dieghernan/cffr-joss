---
title: 'cffr: Generate Citation File Format Metadata for R Packages'
tags:
  - R
  - cff
  - citation
  - credit
  - metadata
authors:
  - name: Diego Hernangómez
    orcid: 0000-0001-8457-4658
    affiliation: 1
affiliations:
 - name: Independent Researcher
   index: 1
date: 15 May 2021
bibliography: paper.bib
---

# Summary

The Citation File Format project [@druskat_citation_2021] defines a standardized format for providing software or datasets citation metadata in plaintext files that are easy to read by both humans and machines.

This metadata format is being adopted by GitHub as the primary format for its built-in citation support [@github_about_citation].
Other leading archives for scientific software, including Zenodo and Zotero [@druskat_stephan_making_2021], have included as well support for CITATION.cff files in their GitHub integrations.

The cffr package provides utilities to generate and validate these CITATION.cff files automatically for R packages [@R_2021] by parsing the DESCRIPTION file and the native R citation file.
The package also includes utilities and examples for parsing components as persons and additional citations, as well as several vignettes which illustrate both the basic usage of the package as well as some more technical details about the metadata extraction process.

# Statement of need

# Acknowledgements

# References
