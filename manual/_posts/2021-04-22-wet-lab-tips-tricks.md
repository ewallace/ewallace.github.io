---
layout: post
title: "Wet lab tips and tricks"
description: "Miscellaneous tips and tricks for the wet lab in Waddington building"
about: true
author_handle: ew
tags: [labmanual, wetlab]
---
{% include JB/setup %}

# Wet lab tips and tricks

This is a page for the random tips and tricks

- how to operate machines
- how to move data between machines
- how to get stuff, e.g. dry ice

Remember, this is going to be on a public website, so no passwords or personal info.

## Ordering outside of Sciquest

If you need to order something that is not available on Sciquest and asks for a lab address, please make sure it gets to Graham Nicolson in Roger Land Stores. Use the address:

Edward Wallace lab (HELP: is that correct? Otherwise how will it get to us?)  
c/o Graham Nicolson  
University of Edinburgh  
School of Biological Sciences  
G27 Roger Land Building  
Alexander Crum Brown Road  
Edinburgh  
EH9 3FF  

This ensures the item is delivered to the right Stores and which is helpful for deliveries outside of core hours or to prevent it from going to engineering stores or anywhere else.

## Dry ice

Mostly for dry ice we get this from the Swann building lobby; ensure you have card access to the Swann building.
Before getting dry ice, please check with Greg Anderson that there is some available – it is purchased by the Wellcome centre and they don’t always have enough to share.

HELP: HOW DO WE ORDER DRY ICE IF THEY DON'T?

## DeNovix / nanodrop

To move data from from the nanodrop to lab notebook or datastore, you can put the file onto a USB drive.
From the Report or Graph screen, data can be exported and saved to a FAT32 formatted USB drive.
A pdf can also be generated and saved. On the Graphs page spectral graphs can be screen captured and the png file may be exported and saved to a USB drive.

The nanodrop is also connected to the network, and it is theoretically possible to export by email.
For more information, see the Data Export and Print Options section of the [Denovix DS-11 user guide](https://www.denovix.com/pdf/ds-11-series-user-guide.pdf).


## Lab tablet computers

We have three lab tablet computers, two running android for notesm photos, etc., and one windows for the little microscope and scanners.

### Android tablets

HELP

### Windows tablet

HELP

## qPCR Analysis

On the computer connected to the Roche Lightcycler 480 qPCR machine in 3Waddington 3.18, the generated files are stored in:
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
