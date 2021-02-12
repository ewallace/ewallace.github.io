---
layout: post
title: "Where data belongs"
description: "Guidelines for storing and organizing data in the Wallace lab"
about: true
author_handle: ew
tags: [labmanual, newstart]
---
{% include JB/setup %}

{:toc}

# Guidelines for storing and organizing data in the Wallace lab

All data must be securely stored and backed up, usually to the lab's datastore space `wallace_rna`. 

Data must also be findable, organized, and described, usually with a `README.txt` or `README.md` file that describes the contents of each directory.

## Resources on dealing with data

Dealing with data is important and complex.
Here are some helpful resources that make it easier to be better.
The first two papers are essential reading.

* [Good enough practices in scientific computing](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005510)
* [How to Share Data for Collaboration, Shannon E. Ellis & Jeffrey T. Leek](https://doi.org/10.1080/00031305.2017.1375987)
* [Edinburgh's BioRDM team](https://www.ed.ac.uk/biology/research/facilities/research-data-management)
* To be continued...

TODO: add data management plans from Wellcome grant.

TODO: make a plan for storing microscopy images.

# wallace_rna on datastore

## Datastore Contents

* quota.txt - automatically generated file that keeps track of data usage compared to quota

* admin - lab administration, inventories, etc.
* bigdata - big data like (raw) sequencing and proteomics datasets
* data - everyday lab data, images, tables, qPCR, etc etc
* datasync - use for sharing data outside the group with the [datasync dropbox-like service](https://www.ed.ac.uk/information-services/computing/desktop-personal/datasync)
* LabMemberContactNos - emergency contact numbers for people who use the wet lab
* manual - contains a previous version of the lab manual from 2019
* presentations - copies of presentations from lab meetings
* riboviz - data related to the riboviz project [riboviz github](https://github.com/riboviz)

Folder organization and contents are described in detail below.

## wallace_rna/admin/

TODO: write this.

### wallace_rna/admin/Inventories

### TODO: REVISE THESE Guidelines for organising glycerol stock strains in datastore

Information on all Fungal and E.coli strains available in the lab are recorded in an Excel spreadsheet called `Edward Lab Database` within the `Strains_and_Associated_Info` Folder in datastore: `wallace_rna/admin/Inventories`. This spreadsheet is divided up into separate sheets for `Yeast` (ie., S.cerevisiae) , `Cryptococcus` and `Bacteria` (ie., E.coli stocks of plasmids). When you make new strains, full details need to be entered into this spreadsheet.

The `Strains_and_Associated_Info` folder also includes additional folders and files:

- **`JA_chimeras_library_yeast_glycerolstock`** – Jamie’s YeastFab database spreadsheet and platemaps of 96-well storage locations together with explanatory `Readme` files as .pdf or .Rmd documents. This folder also contains a subfolder entitled 'JA_chimeras_snapgene_vector_maps' which contains the snapgene vector maps and sequencing trace files verifying the assemblies.

- **`S_cerevisiae_gRNA_plasmids`** -  Snapgene files of gRNA/Cas9 plasmids already existing in the lab - these are linked by name to the relevant entry of the plasmid stock in the `Bacteria` page of ` Edward Lab Database`.

- **`PrimersToTestYeastDelStrains`** – a list of PCR primer sets from the Yeast Deletion Collection that have been used to test deletion strains we already have, together with the expected sizes of their PCR products.

- **`YeastDeletionCollection_Check Primers_PCR_sizes`** - Full list of Primers and Expected PCR product sizes for all of the Yeast Deletion Collection Strains.

- **`YeastDelStrainsfromFoundryin96WellPlate`** – a spreadsheet with the position of a number of yeast deletion strains we got from the Genome Foundry in a 96-well plate.

- **`egf_strains_catalog`** – a list of yeast strains available from the Genome Foundry 

- **`-80 freezer storage locations`** – a spreadsheet showing where communal and personal frozen stocks are kept in the -76oC Freezer – this still needs to be updated to provide space for Rachael . There is also an explanatory `-80 freezer ReadME` file.

- The **`CramerLabDelStrains PCRCheck Primers`** Folder contains snapgene files for CCR4 and POP2(CAF1) genomic sequences together with PCR check primers.

## wallace_rna/bigdata - big data like (raw) sequencing and proteomics datasets

TODO: write this.

## wallace_rna/data - everyday lab data, images, tables, qPCR, etc etc

This folder is organized primarily by date, then name `yyyy/mm-mmmm/name`.
We use years (e.g. `2021`) and months (e.g. `01-Jan`) to ensure that the contents display in consistent order.

For example, the directory `wallace_rna/data/2020/07-Jul/Edward/Ssd1_reportergenes_5UTRonly` contains Edward's data from July 2020 on some Ssd1 reporter genes, where the Ssd1 recognition site is on the 5'UTR.

If you have some data that does not easily lend itslef to being sorted 
TODO: Explain how to integrate with github, probably by just copying github repositories here.

Remember that data on datastore should also be linked to from the relevant lab notebook page in RSpace.


## wallace_rna/datasync - use for sharing data outside the group 

The university's [datasync dropbox-like service](https://www.ed.ac.uk/information-services/computing/desktop-personal/datasync).

## wallace_rna/LabMemberContactNos - emergency contact numbers for people who use the wet lab

TODO: write this.

## wallace_rna/manual - contains a previous version of the lab manual from 2019

TODO: decide what to do with this.

## wallace_rna/presentations - copies of presentations from lab meetings

TODO: write this.

## wallace_rna/riboviz - data related to the riboviz project 

The project is at [riboviz github](https://github.com/riboviz).

Some of the data are too large for github, so they live here.
