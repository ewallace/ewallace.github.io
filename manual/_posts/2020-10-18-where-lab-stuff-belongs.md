---
layout: post
title: "Where lab stuff belongs"
description: "Guidelines for materials, equipment, reagents, strains, in the wet lab space."
about: true
author_handle: ew
tags: [labmanual, newstart]
---
{% include JB/setup %}

# Guidelines for materials, equipment, reagents, strains, in the wet lab space.

This document describes where we keep things in the wet lab.

It also describes how we keep track of new materials that we generate, such as DNA, plasmids, and yeast strains.

It’s important that before you begin any work in the wet lab, you have access to the Datastore – please see [newstart page in the lab manual](newstart) for information on how to set this up.

## Inventory - everything we have in the lab

The inventory is stored on the Datastore using the following filepath
`csce.datastore.ed.ac.uk/csce/biology/groups/wallace_rna/admin/Inventories/Consumables/Wallace_Lab_Inventory.xlsx`.

This spreadsheet contains details on everything that we have in the lab, split into 5 separate tabs; Consumables, Reagents, Antibodies, Chemicals and Equipment. There’s a column for item name, source (meaning the company that it is ordered from), catalogue number (important for reordering the item on Sciquest), quantity (how many were purchased at each time) and storage location. There’s also a separate column for comments on any of the items i.e, out of stock, long lag time etc. 

## Inventory ordering and tracking

This inventory sheet doubles as our order tracking system. Currently, the bulk of the ordering is carried out by Rosey Bayne and Laura Tuck. If you have a Sciquest account and order your own reagents/consumables, please specify what you are ordering in the “Orders” channel on Slack, and add details on to the spreadsheet. If you do not have your own Sciquest account, please give details of what you would like to order, catalogue number and quantity on the “Orders” channel on Slack.

After an item has been ordered, it will be highlighted in red on the inventory spreadsheet. If you are in the lab when the order comes in, please make sure to put the item in its correct location, and once you have done this please turn the text for this item back to black on the inventory spreadsheet. If you are unsure about storage of new items, please check the MSDS sheet if applicable, or ask another lab member to help you out with this. 

## Strains, Plasmids, etc.

For DNA and plasmids, everyone has space in our -20ºC freezer in room 2.19 to store working stocks for daily use. We also have a lab fridge in room 2.19, where bacterial/yeast plates can be stored in the short-term whilst experiments are ongoing. 

It is essential to have long-term stocks of all plasmids (stored in bacteria/yeast), and all edited _S. cerevisiae_ and _C. neoformans_ strains. 
It is also essential to track the data about strains in a consistent format.
This is essential, because future you, others in the lab, and collaborators, need to be able to rely on the strains and build on your results.
For strains that make it to a publication, those strains need to be available to send to other researchers for years into the future.

**Please ask on the #lab channel on slack if there is any doubt at all about any of this.**


## Guidelines for making and storing glycerol stocks

Glycerol stocks at -80ºC store yeast and bacteria indefinitely.

When making new strains, it is worth making temporary glycerol stocks of a number of clones from your transformations while you verify them so that they do not acquire additional random mutations. These can be made in sterile Eppendorf tubes by mixing 100ul of o/n culture in the relevant growth medium (with selection if necessary) with 100ul 30% glycerol in water or growth medium and stored in your own space in the -80ºC Freezer.
Once verified you should streak these stocks out on relevant growth media plates, grow up o/n cultures and make duplicate stocks of each strain in cryo-tubes by mixing 900ul of o/n culture with 900ul 30% glycerol in water or growth medium, put a cap in the top of each tube and label both the cap and the side of the tube with an indelible marker pen. 
One tube should go into each of the 2 relevant strain boxes (yeast/ Crypto/ E.coli (Set A and B)) in Shelf1/StackA(SetA) and Shelf2/StackA(SetB). 
For many mutant strains, e.g. CRISPR mutants, it is worth freezing more than one independent transformant of the strain if you have them – keep the same strain name but add a suffix (eg. yRB002.2 and yRB002.3).

[A printable version of this protocol is on protocols.io](https://www.protocols.io/view/storing-glycerol-stocks-bpkwmkxe).

## Yeast strain information to record in lab database

For yeasts (*Saccharomyces*, *Cryptococcus*, *Candida*, etc.), you need to systematically record full details of the strain.

* Name - id of strain, e.g. the second strain of yeast made by Rosey Bayne is `yRB002`.
* Alias - short descriptive name for strain, (*eg.* `PAB1-Clover`).
* Genotype - systematic description of yeast genotype, as described in [Getting Started With Yeast, section on Genetic Nomenclature](https://www.sciencedirect.com/science/article/pii/S007668790250954X).
* Relevant Genotype - the key genes or mutations that the strain is used for.
* Comments - useful information about the strain and any other relevant info (you can get an idea of what is required by looking at existing records).
* Parent Strain - the id of strain that was the parent of the transformed strain. This should be identical to the id in the lab database. For external strains, this may be found in the publication reference; for some strains it may not be relevant.
* Source - your name if you made it or who/where you got it from.
* Growth Medium - including antibiotics where relevant.
* Date - date entered to database
* Box - Box number where strain stored
* Position in Box - location of that tube
* Reference - to publication, if relevant; including doi.
* Links - links to relevant Snapgene File(s) in datastore.




### Examples

TODO: give a couple of examples, and links to nomenclature.


## Plasmid information to record in lab database

* Name - id of plasmid
* Alias - plasmid  description
* Comments - information about the strain - (*eg.* `this strain is dam+ so plasmid isolated from it will not cut with BclI. You need to transform the plasmid into a dam- strain before isolating plasmid to clone gRNAs but dam- strains are unstable so not suited to making frozen stocks)
* Background - Host strain (*eg.* ccdb, TOP10, NEB5alpha, *etc.*)
* Source - your name if you made it or who/where you got it from.
* Media - growth medium and relevant antibiotic fto maintain selection.
* Date - date entered to database.
* Box- Box number where strain stored.
* Position - location of that tube in the box.
* Link to plasmid map - link to plasmid map/ Snapgene file in datastore




Please refer to ["Where data belongs" section of lab manual](where-data-belongs) for more information on strain organisation in datastore.
