---
layout: post
title: "Lab tips and tricks"
description: "Miscellaneous tips and tricks for the wet lab in Waddington building and other things"
about: true
author_handle: ew
tags: [labmanual, wetlab]
---
{% include JB/setup %}

* TOC
{:toc}

# Lab tips and tricks

This is a page for the random tips and tricks, such as

- how to operate machines
- how to move data between machines
- how to get stuff, e.g. dry ice
- logistics such as buying things

Remember, this is going to be on a public website, so no passwords or personal info.

## Ordering outside of Sciquest

If you need to order something that is not available on Sciquest and asks for a lab address, please make sure it gets to Graham Nicolson in Roger Land Stores. Use the address:

Edward Wallace lab  
c/o Graham Nicolson  
University of Edinburgh  
School of Biological Sciences  
G27 Roger Land Building  
Alexander Crum Brown Road  
Edinburgh  
EH9 3FF  

This ensures the item is delivered to the right Stores and which is helpful for deliveries outside of core hours or to prevent it from going to engineering stores or anywhere else.

Soon (July 2022) Sciquest will cease to be used, and be replaced by People and Money.
Pray for us.


## Sending and delivering reagents

To send things to another lab or request from elsewhere, you can use FedEx or DHL arranged via the Stores team.
The procedure is basically the same if you are sending or receiving.

1. Email swann.stores@ed.ac.uk with saying that you need to send or receive a package. Include the address, describe the contents (including ice or dry ice), and the approximate size and weight. FedEx and DHL deliver to different regions, if in doubt ask the stores team which carrier to use.
2. If RECEIVING, stores team will send you a label and maybe a customs form, forward this to the people sending you stuff.
3. If SENDING, 
  - scavenge for shipping material, containers, etc., it's usually possible to find something
  - make up your package
  - include paperwork inside describing the contents
  - address it including the recipent's address on the front of the package, our address on the back of the package, both with contact phone numbers
  - seal the package
  - take package to Roger Land stores during working hours
  - ask for a tracking number and email that to the recipient, along with a description of the contents


## How to print posters

For example, posters for conferences.

1. Get in touch with the [King's Buildings Copy Centre](https://www.ed.ac.uk/printing/photocopying) and find out the price of the poster you want. Email kbcopy@ed.ac.uk or call them.
2. Email Graham and Davey at swann.stores@ed.ac.uk with subject: "eIT code for poster". Specify the size, type (e.g. fabric), and quoted price of the poster from the Copy Centre, and give them the full grant code (6-digit cost centre, 6-digit grant code).
3. Graham and Davey will email you back with the eIT code.
4. Send the eIT code back to the Copy Centre with the pdf of your poster and repeat your size/type requirements.
5. When the Copy Centre emails you to say the poster is ready, pick it up from JCMB (follow the signs).


## Dry ice

Dry ice is stored in the blue insulated canister in the Freezer room in Waddington basement.
Make sure to read & respect safety and risk assessments: dry ice causes burns.

We buy dry ice from [Chemistry Stores](https://www.chem.ed.ac.uk/research/facilities) in the [Joseph Black building](https://www.ed.ac.uk/maps/maps?building=0632).

1. Point your web browser to [eStores](http://www.estores.finance.ed.ac.uk/) and purchase dry ice, usually 2x 10kg bags.
2. Go to chemistry stores with a trolley, another person, and insulated gloves. If in doubt ask a servitor for directions - it's past the mass spec room.
3. Collect dry ice, bring it back on the trolley, and deposit it in the blue canister. Be careful because dry ice is heavy and dangerously cold. That's why you need the other person, the trolley, and the gloves.


## DeNovix / nanodrop

To move data from from the nanodrop to lab notebook or datastore, you can put the file onto a USB drive.
From the Report or Graph screen, data can be exported and saved to a FAT32 formatted USB drive.
A pdf can also be generated and saved. On the Graphs page spectral graphs can be screen captured and the png file may be exported and saved to a USB drive.

The nanodrop is also connected to the network, and it is theoretically possible to export by email.
For more information, see the Data Export and Print Options section of the [Denovix DS-11 user guide](https://www.denovix.com/pdf/ds-11-series-user-guide.pdf).

## Plate reader booking

For measuring cell growth and fluorescence we use the 4 [TECAN Infinite 200 PRO plate readers](https://lifesciences.tecan.com/plate_readers/infinite_200_pro) in Waddington 2.16 (small dark room off the main lab space).
Plate readers 1 & 2 are M200s with monochromators that can detect a wider variety of wavelengths.
Plate readers 3 & 4 are F200 with fixed-wavelength filters for OD600, mTurquoise (430ex/485em), GFP (485ex/535em), and a red set (check!).

Ivan Clark is in charge of the plate readers, email him at ivan.clark@ed.ac.uk to ask to be added to the booking system.
You can then book any of the 4 available plate readers through the [SynthSys scheduler](http://synthsys.bio.ed.ac.uk/biosched/).
You must ask Ivan and/or an expert in our lab to go through plate reader usage before making your first booking.
It is important to make sure you're fully trained on the plate readers before using them, because they like to break and many people rely on them working.


## Lab tablet computers

We have three lab tablet computers, two running android for notesm photos, etc., and one windows for the little microscope and scanners.

### Android tablets

HELP

### Windows tablet

HELP

## qPCR Analysis

On the computer connected to the Roche Lightcycler 480 qPCR machine in Waddington 3.18, the generated files are stored in:
`My documents > Program files> Roche> Light cycler 480> Bin`

Save multiple files directly from the Lightcycler software, ensuring that your name and the date 20yy-mm-dd are in the file title:
1. From the navigator page select your experiment and export data in native .ixo format.
2. From the same navigator page, export full data in plain-text .txt format.
3. For Ct/Cq values, from the analysis page, go to "Ct values, fit points", calculate Ct values, then export the whole Ct table in plain-text format. If you used only some of the wells, click and drag the mouse over the wells you have used in your plate to highlight them before exporting.
4. For Absquant/2nd derivative max. Export the .ixo AND .txt files. 

Why both filetypes? 
The `.ixo` files are good if you ever wanted to open them on the Roche lightcycler software again.
The `.txt` files are good if you want to do anything else with the files, for example open in R or analyze with [tidyqpcr])(https://github.com/ewallace/tidyqpcr).


## Transformation fmol calculator

This website can be used to calculate fmol concentrations for insert:vector for transformations.

https://www.bioline.com/media/calculator/01_07.html


## Fragment Analyzer Maintenance

There is a red folder next to the Fragment Analyzer in room 3.18 containing all the protocols and weekly/monthly maintenance schedules. 
Maintenance of the Fragment Analyzer is the responsibility of all users. 
Please fill in the forms in the red folder when carrying out any maintenance tasks. 
These include changing buffers. 
If the forms are full new ones can be printed off from data store under `wallace_rna/admin/Fa Maintenance schedule`.

Any questions, ask Liz Hughes.


## Tip for making glycerol stocks in bulk

- start by using a sterile 24-well plate or 96-well plate
-	If sterile plates are unavailable, you can perform UV sterilization using the UV Crosslinker next to the DeNovix/nanodrop.
-	In a sterile environment, fill wells in the storage plate with 50 µL of sterile 30-50% glycerol. You can use the multichannel dispenser for efficiency.
-	Transfer 50 µL of overnight culture to each well. Remember to accurately note down the well corresponding to each strain (have an excel sheet ready before preparing your stocks).
-	Cover the plate with sterile adhesive film and mark it for easier orientation. Label your plate and note down its location in the -80 freezer. 
-	Upon verification of strains, you can now streak out the small glycerol stocks to make proper 1ml stocks.
-	When streaking out, use a scalpel to cut the covering only above the well you want to streak out to prevent contamination to other wells. Use new sterile pipette tips for this. 
-	Once done, use new adhesive film to re-cover the opened well.

## Sterilizing multiwell plates using UV Crosslinker

HELP! 
How do I use the UV Crosslinker? How long should I sterilize?


## Sanger Sequencing with MRC PPU Dundee

We use [MRC PPU in Dundee](https://dnaseq.co.uk) for routine Sanger sequencing of plasmid segments and PCR products.
Wallace lab code is 2248, and the lab address as the invoice address.
Sign up for an account on https://dnaseq.co.uk and ask to be added to the lab list.
Please use our spend-down account that currently costs £3.50 per sequencing reaction.

To ship samples, simply prepare as per instructions on the website in 1.5 ml Eppendorf tubes, seal tubes with parafilm and put into a plastic bag (the bags that PCR tube strips come in are perfect for this).
Either print off the sample label OR write down the Order Reference (will be in the format yourusername-dd-mm-yyyy-xxx) and add this to the bag with the samples.
Put the bag in a brown envelope (we can get these from Roger Land stores and there's currently a small stash in the filing cabinet in the printer room) and address it to: 

```
DNA Sequencing and Services
Medical Sciences Institute
School of Life Sciences
University of Dundee
Dundee
DD1 5EH
UK
```

You can then just put the envelope in the Mail Out box in Swann foyer.


We are about to trial whole-plasmid sequencing with Plasmidsaurus (see below) so we expect to do more whole-plasmid sequencing and less Sanger sequencing of segments, from now on.


## Whole-plasmid sequencing with Plasmidsaurus

New June 2022, there is Plasmidsaurus dropbox at Chancellor's Building, Little France. Plasmidsaurus (https://www.plasmidsaurus.com) offer whole-plasmid sequencing at $15 / sample, see their website for details.

You can drop samples in the box directly, or via internal mail. To send by internal mail. Put your sample packet/envelope in an internal mail envelope marked "Chancellor's Building Reception, Plasmidsaurus Dropbox, Bioquarter/Little France" Prepare samples according to [plasmidsaurus guidelines](https://www.plasmidsaurus.com/instructions/), including ordering/payment information (HELP).

Collection is just once a month at the moment. The first Thursday of every month at 9am. First collection is 7th of July 2022. If there is enough initial use (which seems likely), frequency will go up to weekly or bi-weekly.


## High-throughput sequencing at WTCRF genetics core

Currently we do all our high-throughput sequencing (RNA-seq, library prep, self-prepared libraries, Illumina) at the [WTCRF genetics core](https://www.ed.ac.uk/clinical-research-facility/core-services/genetics), which is at Western General Hospital campus just across town.
Discuss your experimental goals and design with Edward first and we will then contact the genetics core team.
