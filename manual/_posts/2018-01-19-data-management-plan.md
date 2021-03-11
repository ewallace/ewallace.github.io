---
layout: post
title: "Data Management Plan"
description: "Overview of principles for our data management for academic projects"
about: true
author_handle: ew
tags: [labmanual, newstart]
---
{% include JB/setup %}

{:toc}

# Data management plan 

Edward Wallace, as submitted Wellcome Trust Sir Henry Dale Fellowship, 1 June 2017

This document gives an overview of principles for our data management for academic projects; practical guidelines for organizing data are in [where data belongs](where-data-belongs).

## Will the proposed research generate data or software outputs that hold significant value as a resource for the wider research community?

The proposed research will generate data and software that is designed to be reusable by other researchers. My research has relied on re-analyzing raw and processed data from other researchers, and on using research software my colleagues have freely shared. I consider it a fundamental responsibility as a scientist that I share in return. I will place all relevant data and software on publicly available online archives. The direct costs of this data sharing are low, but the commitment of time to organize the data is crucial.

All aims will generate extensive RNA-sequencing data. Aim 1 will generate RNA-seq data on chimeric S. cerevisiae mRNAs in different environmental conditions. Aim 2 will generate CRAC/RNA-seq data on Ssd1 binding sites and the S. cerevisiae stress response. Aim 3 will generate extensive RNA-seq data on C. neoformans environmental adaptation. Aims 2 and 3 will also generate more limited proteomics (MS/MS) data.

The software developed to analyze the data, notably for the analysis of normalized time-series data, will also be valuable to researchers conducting analogous experiments.

*There are no ethical challenges to sharing the proposed data*, as it will all come from fungi. 

Raw data will comprise standard .fastq files for RNA-seq, on the scale of dozens of terabytes. As soon as they are obtained, raw data files will be placed in read-only folders on the Bioinformatics Core servers at the Wellcome Trust Centre for Cell Biology, which has secondary backup in a different building, and separately on an external hard drive. The access cost of storage is included in the proposed budget. This raw data will be accompanied at birth by metadata files describing the acquisition in detail, including describing the conditions (date, replicate, growth conditions, etc) for each file. As soon as possible, and before the time of publication, raw RNA-seq data will be archived at the [Gene Expression Omnibus](https://www.ncbi.nlm.nih.gov/geo/), which doesn’t charge for data submission. 

Proteomics data generated in the course of the grant will be made available similarly, including .raw files for MS/MS on the [PRIDE archive](https://www.ebi.ac.uk/pride/archive/), which also doesn’t charge for data submission. 

Processed data and scripts such as gene-level summaries, and all data and code necessary to generate published figures, will be version-controlled and backed up using [GitHub](https://github.com/). At publication, these will be placed on the [Dryad repository](http://datadryad.org/). As in my recent publications, this will include the data, and computer scripts in an open-source language (R), necessary to re-create the figures. I will make interactive data visualization tools to help my own group and collaborators understand the data, and also share them publicly (e.g. [heat aggregation data visualization](http://drummondlab.org/data/heat-aggregation-yeast-visualization)). 

Ideally, the software I develop to analyze data will be general and portable enough to be shared in a standalone version, for example as an R package on CRAN or the Bioconductor repository. If necessary, I will engage bioinformaticians or research software engineers to ensure that the software is robust and genuinely reusable.

I aim to include in a research publication all successfully quality-controlled data that is collected as part of this grant. At a minimum, I would share in Wellcome Open Research, or a data-only publication such as Data In Brief that assigns the data a DOI, to enable the data to be discovered and used.

### Notes added later

We have recently been using [zenodo](https://zenodo.org/) and [figshare](https://figshare.com/) more than Dryad.
For examples, see the links in recent [papers](papers/).