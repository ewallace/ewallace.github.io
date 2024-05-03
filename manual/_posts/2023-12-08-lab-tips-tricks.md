---
layout: post
title: "Lab tips and tricks"
description: "Miscellaneous tips and tricks for the wet lab in Waddington building and other things"
about: true
author_handle: ew
tags: [labmanual, wetlab]
---
{% include JB/setup %}

# Lab tips and tricks

This is a page for the random tips and tricks, such as

- how to operate machines
- how to move data between machines
- how to get stuff, e.g. dry ice
- logistics such as buying things

Remember, this is going to be on a public website, so no passwords or personal info.

* TOC
{:toc}



# Ordering

## Overview and links

We are now (2023) doing all ordering through the new [People & Money system](https://www.ed.ac.uk/staff/services-support/hr-and-finance/people-and-money-system).
This is widely acknowledged to be a disaster and will hopefully get better in the coming months.
People may refer to it as "P&M" or "Pain & Misery".
Currently in the lab Liz and Domenico are the people who know most about using P&M.

[Link to access people & money](https://elxw.fa.em3.oraclecloud.com/fscmUI/faces/FuseWelcome).
After logging in using single sign-on (SSO, also known as EASE password) click on the "procurement" tab, then the "shop" button.

The [University procurement site has details of the approved university suppliers.](https://www.ed.ac.uk/procurement)
Also for "punchout", that is ordering through a supplier's own website using the university's account, see [approved supplier page](https://uoe.sharepoint.com/sites/Procurement2/SitePages/Approved-Suppliers.aspx).

Some reagents are in-stock on campus at stores locations.
[This page has a list of the different stores and an up to date list of items available, including order codes. It gets updated regularly.](https://www.ed.ac.uk/procurement/stores-operations)

Here is [School of Biological Sciences People and Money Help Site](https://uoe.sharepoint.com/sites/SchoolofBiologicalSciences-PeopleMoney)


## Get the address, VAT, and intended use right for orders

Make sure orders get to School of Physics Stores. 
For delivery address on the requisition in P&M you HAVE to put in:
**School of Physics Stores - James CLerk Maxwell Building**.
or else I am told that "all hell will rain down on to you" - I think hell rains down mostly in the form of emails, also, the order will not arrive.

Also, to place an order successfully you have to....
- For lab reagents that are reasonably described as used in medical research (we work on fungal pathogens!):
  - Attach the VAT certificate (on slack/orders channel)
  - Select the intended use for EACH line on the requisition as shown below:
  - 01 - ZR MEDICAL/VET, CERT REQUIRED - Purchase, repair or maintenance of equipment, software, products and substances used SOLELY in medical and veterinary research, training, diagnosis, treatment and care.
- Office equipment such as stationery is not VAT exempt and has use code 03 instead.
- Double check your delivery location and Charge account BEFORE submitting the order.

If in doubt, ask for help before you submit.

# Ordering Oligos

We order our oligos from IDT https://www.idtdna.com.
We have prepaid for oligos using an oligocard.
If you are a PhD student or other person with your own funding, you may wish to purchase a separate oligocard.


To order via the IDTwebsite:

- **Sign in**: We have an account for the lab, username `Wallace Lab`, email wallacelabrna@mlist.is.ed.ac.uk,  ask someone for the password.  
- Order your oligos. If you have previously designed
- **Click**: Continue  
- **Click**: Add to cart  
- **Click**: Checkout  
- Leave the shipping and billing details as they are.   
- **Select**: This purchase is eligible for VAT zero.  
- Enter the VAT Number: 592 9507 00  
- **Click**: Continue  
- **Select**: Oligocard  
- Enter the oligocard Number. Lab oligocard as of Dec 2023 is **818812219378**.
- Add your email address  
- **Click**: Submit order  


## Tips on designing primers for qPCR:

For quantitative PCR primer design there are some other important tips:

- Sign in to IDT as above
- Select Tools > qPCR assay design  > Primerquest Tool  
- Enter the sequence and give it a name.  
- **Choose**: qPCR 2 primers Intercalating dyes. Check ALL the parameters.
- You will be taken to a new page with 5 options of primer pairs called assays.  
- Use netprimer to check each primer set for secondary structures. This is important as secondary structures can severely impact sensitivity.  
- Go to www.premierbiosft.com/netprimer  
- Create your own account.  
- Read "Primers oligo architect glossary" in wallace_rna > admin > useful information. This will explain the different parameters and what you should be looking for in a good primer pair.  
- Select 2 of the primer pairs or assays. (1 might not work; select 2)
- **Click**: Add to Order > Forward and Reverse Primers > Oligos in tubes
- Continue your order as above.

Note: we should update our protocol to include these tips


# Sending and delivering reagents (NEEDS UPDATING Dec 2023)

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
  - take package to Physics stores during working hours
  - ask for a tracking number and email that to the recipient, along with a description of the contents


For reagent requests from other labs (non-PO so non-P&M) use the address:

Edward Wallace lab  
c/o School of Physics Stores
James Clerk Maxwell Building
Kings Buildings
Peter Guthrie Tait Road
EDINBURGH
Midlothian
EH9 3FD
UNITED KINGDOM

This ensures the item is delivered to the right Stores and which is helpful for deliveries outside of core hours or to prevent it from going to engineering stores or anywhere else.


# How to print posters

For example, posters for conferences.

0. Plan ahead, send your poster for printing 1-3 working days before you need to pick it up. This means ask colleagues inc. Edward to give comments on your poster 1-2 weeks in advance.
1. Get in touch with the [King's Buildings Copy Centre](https://www.ed.ac.uk/printing/photocopying) and find out the price of the poster you want. Email in pdf format to kbcopy@ed.ac.uk or call them. 
2. Fill in the Interim Purchase Order Request Form (it's on slack/orders), including the quoted price of the poster from the Copy Centre, the project code (8-digit, underscore, 8-digit, ask Edward or your PhD program). The Task number is *1* and the expenditure type is *"Consumables"*.
3. Return the form to the Copy Centre, kbcopy@ed.ac.uk
4. When the Copy Centre emails you to say the poster is ready, pick it up from JCMB 2300 (follow the signs).



# Dry ice

We have a temporary solution for obtaining dry ice.
First check the dry ice box in the freezer room to see what's available.

Stevie (building manager at Ashworth) has confirmed that we can take dry ice from the supply at Ashworth as they usually have spare. Please don’t take the entire contents of the box at one time though.
 
The box of dry ice is in the Ashworth 2 loading bay. The door from the outside is locked by the Stores staff at 4pm, or you can go through the building but must have a swipe card to get back in.
 
If anyone isn’t sure how to find it, please give Sean, the Ashworth building assistant, a call on 07827 845717 to show them.


# DeNovix / nanodrop

To move data from from the nanodrop to lab notebook or datastore, you can sent it to yourself via email export. To do that:
* select measurements on the report panel -> tap on share  -> email -> select your name from the drop down menu -> send
* to add your contact to the menu go on the accounts app -> open the dropdown menu -> select address book and add your email

You will receive your data in csv format from wallace_lab_denovix@outlook.com.

Alernatively, you use a USB drive. From the Report or Graph screen, data can be exported and saved to a FAT32 formatted USB drive.
A pdf can also be generated and saved. On the Graphs page spectral graphs can be screen captured and the png file may be exported and saved to a USB drive.

For more information, see the Data Export and Print Options section of the [Denovix DS-11 user guide](https://www.denovix.com/pdf/ds-11-series-user-guide.pdf).


# Plate reader booking

For measuring cell growth and fluorescence we use the 4 [TECAN Infinite 200 PRO plate readers](https://lifesciences.tecan.com/plate_readers/infinite_200_pro) in Waddington 2.16 (small dark room off the main lab space).
Plate readers 1 & 2 are M200s with monochromators that can detect a wider variety of wavelengths.
Plate readers 3 & 4 are F200 with fixed-wavelength filters for OD600, mTurquoise (430ex/485em), GFP (485ex/535em), and a red set (check!).

Ivan Clark is in charge of the plate readers, email him at ivan.clark@ed.ac.uk to ask to be added to the booking system.
You can then book any of the 4 available plate readers through the [SynthSys scheduler](http://synthsys.bio.ed.ac.uk/biosched/).
You must ask Ivan and/or an expert in our lab to go through plate reader usage before making your first booking.
It is important to make sure you're fully trained on the plate readers before using them, because they like to break and many people rely on them working.

# Routine Sequencing
## Sanger Sequencing with MRC PPU Dundee

We use [MRC PPU in Dundee](https://dnaseq.co.uk) for routine Sanger sequencing of plasmid segments and PCR products.
Wallace lab code is 2248, and the lab address as the invoice address.
Sign up for an account on https://dnaseq.co.uk and ask to be added to the lab list.
Please use our spend-down account that currently costs £3.50 per sequencing reaction.

To ship samples, simply prepare as per instructions on the website in 1.5 ml Eppendorf tubes and put into a plastic bag (the bags that PCR tube strips come in are perfect for this).
Either print off the sample label OR write down the Order Reference (will be in the format yourusername-dd-mm-yyyy-xxx) and add this to the bag with the samples.
Put the bag in a brown envelope (we can get these from Physics stores and there's currently a small stash in the filing cabinet in the printer room) and address it to:

```
DNA Sequencing and Services
Medical Sciences Institute
School of Life Sciences
University of Dundee
Dundee
DD1 5EH
UK
```

You can then just put the envelope in the Mail Out box in Swann foyer, which is picked up at around 3pm every day.


## Sanger Sequencing with Azenta GeneWiz

In September 2023 we set up a lab account for Sanger sequencing with GeneWiz/Azenta.

Guide:

1. Go to the [GeneWiz website](https://www.genewiz.com/en-GB/) and log in.
  - Login details can be found within the group datastore in */admin/useful_information/genewiz_account.rtf*
2. To fill a sample sheet go to Genomics Services > Sanger Sequencing Tubes.
  - Write your name in order name.
3. Prepare reactions in 1.5mL tubes.
  - Follow instructions for pre-mixed tubes in the [sample preparation guidlines](https://www.genewiz.com/en-GB/Public/Resources/Sample-Submission-Guidelines/Sanger-Sequencing-Sample-Submission-Guidelines/Sample-Preparation#sanger-sequence).
4. Add barcodes according to the [guide](https://web.genewiz.com/sanger/labellingyoursamples).
  - The barcode number in the sample sheet MUST match the physical barcode sticker on the tube.
  - Physical barcodes stickers are stored in the 2nd drawer underneath the coffee machine in 3.04, in a Yellow DHL envelope labelled ‘GENEWIZ VOUCHERS’.
5. Place your tubes in a Purple Azenta box with the printed order confirmation form, then write the number of samples on a piece of tape and stick it on the outside of the box.
  - Sample boxes are stored in 2nd drawer underneath the coffee machine in 3.04.
  - More sample boxes are found under the dropbox in Swann.
6. Take your samples to Swann. Take an empty box back to the drawer to replace the one you just used. Daily pickup is at 2 pm in Swann foyer dropbox.
7. Wait for results, usually received within 1-2 days.


## Whole-plasmid sequencing with Plasmidsaurus

Plasmidsaurus (https://www.plasmidsaurus.com) offer whole-plasmid sequencing at $15 / sample, see their website for details.

Prepare samples according to [plasmidsaurus guidelines](https://www.plasmidsaurus.com/instructions/). We use a shared lab account to order, details can be found within the group datastore in */admin/useful_information/plasmidsaurus_account.rtf*.

There is a Plasmidsaurus Dropbox in the Swann Foyer, weekly pickup is 1pm on Wednesdays. 

# Lab tablet computers

We have three lab tablet computers, two running android for notesm photos, etc., and one windows for the little microscope and scanners.

## Android tablets

HELP

## Windows tablet

HELP


# qPCR Analysis

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


# Transformation fmol calculator

This website can be used to calculate fmol concentrations for insert:vector for transformations.

https://www.bioline.com/media/calculator/01_07.html


# Fragment Analyzer Maintenance

There is a red folder next to the Fragment Analyzer in room 3.18 containing all the protocols and weekly/monthly maintenance schedules.
Maintenance of the Fragment Analyzer is the responsibility of all users.
Please fill in the forms in the red folder when carrying out any maintenance tasks.
These include changing buffers.
If the forms are full new ones can be printed off from data store under `wallace_rna/admin/Fa Maintenance schedule`.

Any questions, ask Liz Hughes.


# Tip for making glycerol stocks in bulk

- start by using a sterile 24-well plate or 96-well plate
-	If sterile plates are unavailable, you can perform UV sterilization using the UV Crosslinker next to the DeNovix/nanodrop.
-	In a sterile environment, fill wells in the storage plate with 50 µL of sterile 30-50% glycerol. You can use the multichannel dispenser for efficiency.
-	Transfer 50 µL of overnight culture to each well. Remember to accurately note down the well corresponding to each strain (have an excel sheet ready before preparing your stocks).
-	Cover the plate with sterile adhesive film and mark it for easier orientation. Label your plate and note down its location in the -80 freezer.
-	Upon verification of strains, you can now streak out the small glycerol stocks to make proper 1ml stocks.
-	When streaking out, use a scalpel to cut the covering only above the well you want to streak out to prevent contamination to other wells. Use new sterile pipette tips for this.
-	Once done, use new adhesive film to re-cover the opened well.


# Sterilizing multiwell plates using UV Crosslinker

HELP!
How do I use the UV Crosslinker? How long should I sterilize?


# High-throughput sequencing at WTCRF genetics core

Currently we do all our high-throughput sequencing (RNA-seq, library prep, self-prepared libraries, Illumina) at the [WTCRF genetics core](https://www.ed.ac.uk/clinical-research-facility/core-services/genetics), which is at Western General Hospital campus just across town.
Discuss your experimental goals and design with Edward first and we will then contact the genetics core team.

## Downloading high-throughput sequencing data

See more at [fastq directory instructions, in where data belongs manual page](where-data-belongs#fastq-directory-instructions).

The genetics core share data via [Illumina basespace](https://basespace.illumina.com/).
You need to create an account first - go to sign-in page and click "don't have an account" and register.

When your data are ready, the genetics core will send 2 links, one for the run and one for the project. Click on both links and then accept sharing them. See [basespace help](https://help.basespace.illumina.com) for more help.

Next you need to download the data to datastore.
It's recommended to use the [basespace command-line interface](https://developer.basespace.illumina.com/docs/content/documentation/cli/cli-examples).

From [Eddie](https://www.ed.ac.uk/information-services/research-support/research-computing/ecdf/high-performance-computing):

```bash
# log in to data staging node
qlogin -q staging

# change directory to the datastore fastq directory
cd /exports/csce/datastore/biology/groups/wallace_rna/bigdata/fastq

# load basespace
module load igmm/apps/BaseSpaceCLI/0.10.7

# authenticate to basespace:
bs auth

# then log in to basespace on your browser, copy that URL into browser to authenticate

# check that it worked
bs whoami

# List projects! fastq files are in "projects"
bs list projects

# this will give you a project id number XXXXXXXXX and name AB_namebit_dddddd
# update the id and name to correspond to the project you wish to download

bs download project -i XXXXXXXXX -o AB_namebit_dddddd --extension=fastq.gz
bs download project -i XXXXXXXXX -o AB_namebit_dddddd --extension=txt

# move all fastq fiels into a single directory and calculate checksums
mv AB_namebit_dddddd/*/*.fastq.gz AB_namebit_dddddd
md5sum AB_namebit_dddddd/*.fastq.gz > AB_namebit_dddddd/download_checksums.txt

# change file permissions to read-only to make it hard to delete
chmod a=r AB_namebit_dddddd/*.fastq.gz
```

After this, be sure to update the `/wallace_rna/bigdata/fastq/README.md` file.

Then log out of Eddie.


# bifx servers

The bifx (short for bioinformatics) servers are run by Shaun, Dan, and Hywel at the Welcome Centre for Cell Biology in Swann.
Sometimes they are a good option for bioinformatics analysis.

For more information, see the [bifx help page](https://uoe.sharepoint.com/sites/wcbbifx-core?CT=1661952893815&OR=OWA-NT&CID=2b5e67e3-4eb2-f35c-204f-01bde6476818)

From bifx, connect to the lab datastore at:
`/ds_folders/wallace/wallace_rna/`.

Email Shaun Webb and cc Edward if you need to set up a bifx account and connect to the lab datastore.
