---
title: "Functional Enrichment Workshop"
author: 'Australian Biocommons, Sydney Informatics Hub (USYD) and Monash Genomics and Bioinformatics Platform (MGBP)'
date: |
    "November 20, 2024" 
    <img src="logos.png" width="300" alt="Logo"><br>
site: bookdown::bookdown_site
output: bookdown::bs4_book
documentclass: book
bibliography: [book.bib, packages.bib]
description: |
  A comprehensive guide to functional enrichment analysis using both online platforms and command-line tools.
link-citations: yes
github-repo: "https://github.com/MonashBioinformaticsPlatform/Functional_Enrichment_Workshop_2024"
always_allow_html: true
# cover-image: Sydney_informatics_hub_logo.png
---


# Functional Enrichment Workshop

**Welcome to the Functional Enrichment Workshop!** This resource is designed to guide you through the process of performing functional enrichment analysis using a variety of tools and methodologies, both online and via command-line interfaces.

### Instructors

- **Hossein V Kahrood**
  - Lead Instructor, Monash Genomics and Bioinformatics Platform (MGBP)
  - [hossein.valipourkahrood@monash.edu](mailto:hossein.valipourkahrood@monash.edu)

- **Cali Willet**
  - Lead Instructor, Sydney Informatics Hub
  - [cali.willet@sydney.edu.au](mailto:cali.willet@sydney.edu.au)

### Important Links

- **Workshop Page:** [Functional Enrichment BioCommons 2024](https://monashbioinformaticsplatform.github.io/Functional_Enrichment_BioCommons_2024/)
- **Related Publication:** [NeuroMolecular Medicine Article](https://link.springer.com/article/10.1007%2Fs10571-016-0403-y)
- **Degust Tool:** [Degust Comparative Analysis](https://degust.erc.monash.edu/degust/compare.html?code=5b2c7805ab8f8c5f2dc8c72e61b049b0#/?plot=mds)

---

### Getting Started

To begin, we recommend reviewing the [workshop page](https://monashbioinformaticsplatform.github.io/Functional_Enrichment_BioCommons_2024/) for an overview of the content and tools covered. This workshop is structured to progressively build your skills, starting with the basics of functional enrichment analysis and moving towards more complex applications.

Happy learning!

<!--chapter:end:index.Rmd-->


# (PART) Day 1

<!--chapter:end:part-day1.Rmd-->


# Overview

Placeholder


## Functional analysis of -Omics data 
### General information
### Course Objectives
### Target Audience
### Setup Requirements
### Schedule

<!--chapter:end:01-overview.Rmd-->


# Recap

Placeholder


## Functional enrichment analysis
### Why Is It Important?
### When to Use Functional Enrichment Analysis?
### What Are the Input Data?
### Synonyms
## Concepts
## Types of Enrichment Analysis
### Over Representation Analysis (ORA)
#### Input Data
#### Workflow
### Gene Set Enrichment Analysis (GSEA)
#### Input Data
#### Workflow
### Pathway Topology (PT)-Based Enrichment
#### Input Data
#### Workflow
## Annotation Databses
### [GO: Gene Ontology](https://geneontology.org/)
### [KEGG: Kyoto Encyclopedia of Genes and Genomes](https://www.genome.jp/kegg/)
### [Reactome](https://reactome.org/)
### [MSigDB](https://www.gsea-msigdb.org/)
## Common Tools for Doing FEA

<!--chapter:end:02-recap.Rmd-->


# Enrichment Statistics

Placeholder


## <span style="color:orange;">Fisher's Exact Test</span>
## <span style="color:orange;">Hypergeometric Test</span>
####  {-}
## Activity
### **Challenge:** Interactive Calculator {- .challenge}
####  {-}
### **Questions** {- .rationale}
####  {-}

<!--chapter:end:03-stats.Rmd-->


# Example Analysis

Placeholder


## SH-SY5Y Differentiation
## The question: What pathways are involved in SH-SY5Y Differentiation?
## The data : Differentially expressed genes

<!--chapter:end:04-example-dataset.Rmd-->


# Defining the genelist

Placeholder


## Activities
## Common gotcha
## Example

<!--chapter:end:05-genelists.Rmd-->


# Online Tools

Placeholder


## FEA in gProfiler <a href="https://biit.cs.ut.ee/gprofiler/gost" target="_blank"><img src="images/gp2-logo-new.png" alt="g:Profiler Logo" style="height:35px; vertical-align:middle;"></a>
### Steps to perform ORA in g:Profiler:
#### Browse the gProfiler Results
####  {-}
#### Different Backgrounds
#### **Challenge:** How different backgrounds impact the output? {- .challenge}
#### **Questions ** {- .rationale}
### Steps to perform GSEA in g:Profiler:
#### **Challenge:** GSEA with gProfiler {- .challenge}
#### **Question ** {- .rationale}
## FEA in STRING <a href="https://string-db.org" target="_blank"><img src="images/string-logo.png" alt="STRING Logo" style="height:35px; vertical-align:middle;"></a>
### Steps to Perform ORA in STRING:
### Browse the STRING ORA Results
#### Viewers
#### Legend
#### Settings
#### Analysis
#### Exports
#### Clusters
#### **Question** {- .rationale}
### Steps to Perform GSEA in STRING:
### Browse the STRING GSEA Results
## FEA in GenePattern <a href="https://www.genepattern.org/#gsc.tab=0" target="_blank"><img src="images/GenePattern-logo.png" alt="GenePattern Logo" style="height:35px; vertical-align:middle;"></a>
### Steps to Locate GSEA Module in GenePattern:
### Steps to Perform GSEA:
#### Browse the GSEA results
#### **Challenge:** How do different ranking metrics impact the output? {- .challenge}
#### **Question ** {- .rationale}
####  {-}
## FEA in Reactome <a href="https://reactome.org/" target="_blank"><img src="images/reactome-logo.png" alt="Reactome Logo" style="height:35px; vertical-align:middle;"></a>
### Steps to perform ORA in Reactome:
### Steps to perform GSA in Reactome:
### Browse the Reactome results
####  {-}
#### **Question ** {- .rationale}
####  {-}

<!--chapter:end:06-web-tools.Rmd-->


# Reporting results

Placeholder


## In text
## As a table
## As a figure

<!--chapter:end:07-reporting.Rmd-->


# Resources

Placeholder


## g:Profiler / g:GOSt
## PANTHER 
## DAVID 
## Enrichr
## Reactome
## Biocyc
## STRING
## Gene Ontology
## KEGG
## GSEA and MSigDB
## MetaboAnalyst
## Cytoscape

<!--chapter:end:08-resources.Rmd-->


# (PART) Day 2

<!--chapter:end:part-day2.Rmd-->


# R environment set up 

Placeholder


## RStudio basics
## Download input data
## R notebooks 
### Code chunks
### Rendered HTML notebooks
### A fresh workspace
### Working directory
### R packages

<!--chapter:end:09-r-environment-setup.Rmd-->


# ORA with gprofiler2

Placeholder


## Input data 
## Activity overview
## End of activity summary

<!--chapter:end:10-gprofiler2.Rmd-->


# GSEA with clusterProfiler

Placeholder


## Activity overview
## End of activity summary
## Poll

<!--chapter:end:11-clusterprofiler.Rmd-->


# WebGestaltR

LIST OF AMAZING THINGS ABOUT WEBGESTALTR:
- makes great html reports with interactive plots and links to external dbs
- saves the results to disk when running, no need to export stuf and save files manually 
- many dbs and gene lists supported (n = 70) 
- supports metabolomics, with 15 different ID types, see new paper https://academic.oup.com/nar/article/52/W1/W415/7684598#google_vignette 
- can be used for novel species, but i havent tried it yet... 
- does ORA, GSEA, and NTA. I wonder if the NTA works at all for novel species???! 
- super easy to run. many supported namespaces (n = 73), does not require conversions for different functions like clusterProfiler, can even have different napesapce for ORA gene list and background list 
- "Multiple databases in a vector are supported for ORA and GSEA" 

<!--chapter:end:12-webgestaltr.Rmd-->


# Non-model species functional enrichment analysis

Placeholder


## Axolotl functional enrichment analysis
### Background 
### Raw data sources
### Data preparation
#### Annotation files 
#### Reads processing and differential expression analysis
## Activity overview
## R-based FEA
### clusterProfiler
### WebGestaltR
## RNotebook FEA
## STRING FEA
### How do the STRING results compare to those we generated in R? 

<!--chapter:end:13-novel-species.Rmd-->



<!--chapter:end:14-reporting-results.Rmd-->
