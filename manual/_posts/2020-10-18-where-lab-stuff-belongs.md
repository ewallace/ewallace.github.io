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

It’s important that before you begin any work in the wet lab, you have access to the Datastore – please see x page on the lab manual for information on how to set this up.

## Inventory
The inventory is stored on the Datastore using the following filepath
csce.datastore.ed.ac.uk/csce/biology/groups/wallace_rna/admin/Inventories/Consumables/Wallace_Lab_Inventory.xlsx

This spreadsheet contains details on everything that we have in the lab, split into 5 separate tabs; Consumables, Reagents, Antibodies, Chemicals and Equipment. There’s a column for item name, source (meaning the company that it is ordered from), catalogue number (important for reordering the item on Sciquest), quantity (how many were purchased at each time) and storage location. There’s also a separate column for comments on any of the items i.e, out of stock, long lag time etc. 

## Inventory ordering and tracking
This inventory sheet doubles as our order tracking system. Currently, the bulk of the ordering is carried out by Rosey Bayne and Laura Tuck. If you have a Sciquest account and order your own reagents/consumables, please specify what you are ordering in the “Orders” channel on Slack, and add details on to the spreadsheet. If you do not have your own Sciquest account, please give details of what you would like to order, catalogue number and quantity on the “Orders” channel on Slack.

After an item has been ordered, it will be highlighted in red on the inventory spreadsheet. If you are in the lab when the order comes in, please make sure to put the item in its correct location, and once you have done this please turn the text for this item back to black on the inventory spreadsheet. If you are unsure about storage of new items, please check the MSDS sheet if applicable, or ask another lab member to help you out with this. 

## Strains
For DNA and plasmids, everyone has space in our -20ºC freezer in room 2.19 to store working stocks for daily use. We also have a lab fridge in room 2.19, where bacterial/yeast plates can be stored in the short-term whilst experiments are ongoing. However it is very important to have long-term stocks of all plasmids (stored in bacteria/yeast), or edited _S. cerevisiae_ and _C. neoformans_ strains. We follow the below guidelines on making glycerol stocks to do this.

## Guidelines for making and storing glycerol stocks
When making new strains, it is worth making temporary glycerol stocks of a number of clones from your transformations while you verify them so that they do not acquire additional random mutations. These can be made in sterile Eppendorf tubes by mixing 100ul of o/n culture in the relevant growth medium (with selection if necessary) with 100ul 30% glycerol in water or growth medium and stored in your own space in the -80ºC Freezer.
Once verified you should streak these stocks out on relevant growth media plates, grow up o/n cultures and make duplicate stocks of each strain in cryo-tubes by mixing 900ul of o/n culture with 900ul 30% glycerol in water or growth medium, put a cap in the top of each tube and label both the cap and the side of the tube with an indelible marker pen. One tube should go into each of the 2 relevant strain boxes (yeast/ Crypto/ E.coli (Set A and B)) in Shelf1/StackA(SetA) and Shelf2/StackA(SetB). For CRISPR Mutants it is worth freezing more than one isolate of the strain if you have them – keep the same strain name but add a suffix (eg. yRB002.2 and yRB002.3).

For a printout of this protocol, please refer to https://www.protocols.io/view/storing-glycerol-stocks-bpkwmkxe
You need to record full details of strain: Name , Genotype, Background Strain, Source (your name if you made it or who/where you got it from), Growth Medium (including antibiotics where relevant), date entered, location details (Box and Position), any other relevant info (you can get an idea of what is required by looking at existing records). Please refer to the ‘Where data belongs’ section for information on strain organisation in datastore.
