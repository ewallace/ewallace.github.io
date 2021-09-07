---
layout: post
title: "Lab notebook guidelines"
description: "Principles and guidelines for electronic lab notebook entries and organization"
about: true
author_handle: ew
tags: [labmanual, wetlab]
---
{% include JB/setup %}

* TOC
{:toc}

# Why lab notebooks are important

Good record-keeping is an essential part of good work:

- Your lab notebook helps you to remember what you did and why.
- Your lab notebook is the best way to communicate activity and data around the lab.
- Keeping good records is a legal and funder requirement.

The lab notebook belongs to the institution, not to you personally.
Keeping it up to date is a responsibility to yourself, to our research group, and to the institution.

Some scenarios where good lab notebook entries are useful:

- You need to show your last month's data to the PI or a colleague.
- You need to repeat an experiment you last did a year ago.
- A new lab member is comparing two approaches to an experiment, their pros and cons, to plan a new version.
- An experiment that used to work has stopped working, and we need to go over the details of reagents and what has changed.
- You are writing up the methods section of your PhD thesis or paper.
- The reviewers for your paper ask to see other items of raw data.

In all these cases, if you have kept good lab notebooks you and your colleagues will be grateful to past you.
If you have not kept good records, you and your colleagues will be annoyed with, and disappointed in, past you.
You might think you will remember the details, but you won't.
Without good notebook entries, important points will be forgotten, your or someone else's time will be wasted, and you risk accusations of misconduct.

In summary, the lab notebook is a tool to do good work, that is practically useful for you.
Keeping your lab notebook up to date is a non-negotiable requirement for students and staff who work in the wet lab.


# Principles for lab notebooks

*Your experiment is not "done" until it is written up in your lab notebook.*

Your lab notebook should:

- Describe your substantial activities in the lab every day, with dates.
- Describe your work in enough detail to reproduce it.
- Include, or link to, every piece of substantial data that you collect.
- Place your work in the context of larger goals and projects.
- Be updated within a week.

Exactly how these principles are achieved is a matter of judgment.
The rest of this manual page gives suggestions.
A useful test is, would you be able to reproduce the experiment in a year's time working from the lab notebook entry? 
Would someone else be able to reproduce it, a year after that?

You need to set aside both time and mental energy to write the lab notebook.
Good habits help.
For example, you can set up templates for entries for standard experiments that you do.
You can set aside regular time to update the notebook, including with other lab members to create some accountability.

## Work should be FAIR: Findable, Accessible, Interoperable, and Reusable

It is helpful to consider the [FAIR principles for scientific data management](https://www.go-fair.org/fair-principles/), which also apply to protocols, analysis, and methods.

- *Findable:* The first step in (re)using data and protocols is to find them. Your lab notebook entries should be findable by "metadata", for example project, protocol, strain or oligo identifier, or date of creation.
- *Accessible:* Once the user finds the required data you should be able to access it. So if the lab notebook entry mentions a dataset elsewhere (e.g. datastore, lab notebook page), link to it with accession information.
- *Interoperable:* The data usually need to be integrated with other data, and to interoperate with applications or workflows for analysis, storage, and processing. Use standard file formats.
- *Reusable:* The ultimate goal is to optimise the reuse of data, protocols, and methods. You and others should be able to reuse what you have done, to a high standard, and efficiently.


# Examples of what to include and what not

Basically everything that is easy and/or important to include in your lab notebook should be in there.
Information doesn't need to be repeated in multiple notebook entries, because you can hyperlink between entries; as a guide, everything directly relevant to the experiment should be findable (linked to, named, file location described, etc) within 5 minutes.

To inform the judgment call of what to include and what not:

- *Handwritten notes* are fine to include, just take a photo of it and include in with enough typed searchable metadata that you can find it again.
- *Bullet points* are fine, you do not need to write in paragraphs. It's more important to have a terse account that is written quickly than beautiful prose.
- *Say why* you are doing the experiment - briefly state the aim of the experiment and connect/link it to the larger project. You might have a project or subproject aims page you can link to, or a "parts guide" for a group of related strains/plasmids that gets updated as specific parts are made and verified.
- *Conclude* what you learned and what you need to do next, however briefly.
- *Things don't have to work,* include data from all experiments, "successful" or otherwise. 
- *Reusing strains* you should give the strain ID number (e.g. `yVS042`, see [strain descriptions](where-lab-stuff-belongs)), along with a brief description at the top of the entry, e.g. "Pab1-GFP Hsp104-mCherry in BY4741 background". If it's possible or sensible, link to the page that generated/describes the strain. You don't need to describe the strain in detail every time you use it. There may be multiple strains where your favourite gene is tagged with green fluorescent protein, `YFG_GFP` isn't enough, give the strain ID number.
- *Oligos* include the oligo name/ID and sequence the first time you use it, with the certificate of synthesis. For IDT oligos the certificate is available if the person who ordered it logs in to IDT through sciquest punch-out; it's best to add the whole oligo order info to your lab notebook when it arrives. It can be helpful to give each oligo an unambiguous ID number, e.g. `oVS1067`, which is easier to refer to than "YFG1-verifydeletion-set3-rev".
- *Designs* for plasmids, inserts, cloning, etc, should be included in the relevant notebook entries. Usually the design would be in snapgene, genbank, or fasta format, 
- *Plasmid minipreps*, entry should include the name and batch number of the kit you used, and an electronic copy of the nanodrop/DeNovix quantification. You don't need to repeat the entire published protocol.
- *RNA/protein extraction*, entry should include a link to the protocol and describe any modifications you made. All reagents, e.g. buffers, should be described unambiguously. Ideally you would say which batch of buffer (e.g. prep date) you used, or for commercial reagents the batch number.
- *Bacterial or yeast transformations*, since it is so easy to take a photo of the plate of transformants and add it to your lab notebook, please do that.
- *Photos* of tubes, equipment, pipetting layouts, etc - it's also easy to take a photo and shove it in your notebook, why not do that. These photos help address the situation where you leave the lab and think "oh goodness, did I have the samples in the right order?"
- *PCR*, record the program, enzyme, buffer (both with manufacturer, part number, batch number), oligos, template source and concentration. Everything you need to reproduce it. If you follow a standard protocol link to that, and note only the modifications that you make.
- *Reagents should be recorded precisely including manufacturer's part number*, and ideally batch number. Different manufacturers make enzymes (e.g. EcoRI, BsaI) with different capabilities, shipping buffers, etc. PEG comes in many varieties. There can be big batch-to-batch variation in enzymes, bovine serum, etc. Part numbers help reproducibility, while batch numbers help troubleshooting if one batch behaves differently from another. This is not an invitation to overkill: for example you could not the part/batch number in a "parts list" at the beginning of a week of experiments, then use a short name thereafter. It is ok to record batch number by including a photo of the bottle/tube.
- *Strange observations* should be included, for example "a very hot day in lab and my experiment unexpectedly failed, maybe it's the temperature?"
- Please add more examples?


# Raw unedited data must be included

Raw unmodified data must be included or linked to, without exception. 
Usually larger files will be kept on datastore and linked to, see the section on datastore organization in  [the manual page on where data belongs](where-data-belongs).

For example:
- the unedited image file from the imagequant/scanner/tablet/camera. This would usually be in .tif format. See Claus Wilke's chapter on [understanding common image file formats](https://clauswilke.com/dataviz/image-file-formats.html).
- the .txt file of your nanodrop results.
- the .xls file of the plate reader readings.
- the .ixo and .txt files from a qPCR run.
- the exported data from the fragment analyzer (check format).
- the .fastq file from your sequencing run should be placed on datastore and linked to from the relevant lab notebook page when you receive it back.

Quoting the [Leek lab's guide to sharing data](https://github.com/jtleek/datasharing) (which is worth reading in its entirety):

> If you made any modifications of the raw data it is not the raw form of the data.


We have tried to set up the lab to make this easy. 
Almost all instruments are linked to the internet and datastore, so that you can copy your data straight to the right place.
We have android tablets in the lab that you can use to log in to RSpace and deposit photos and notes directly from the lab.

If there are problems, or ideas to make it easier, talk to the rest of the lab.


# Processed and summarized data must also be included

Yes, this means that most notebook entries will include both raw and processed data.
This kind of near-repetition is ok.

For example:
- the annotated image file with a field of view selected that shows your western/microscopy image.
- a summary figure of your nanodrop results comparing yield from different preps.
- summary data and figures of plate reader data.

Whenever possible, include or link to the script that processed the data.

If you processed or obtained data via a website (e.g. gene ontology analysis, RNA folding, qPCR primer design), give enough information to be able to repeat it.


# Give your files good names

Ending the filename with a data in standard format `yyyy-mm-dd` means that you can unambiguously link the data to the day it is collected.
For example `Vlad-platereader-rbpmutants-replicate1-2021-04-15.xls` tells us that these are data from Vlad's plate reader experiment, on rbp mutants, replicate one, on the 15th April 2021.
Then it is easy to reunite with Vlad's lab notebook from 15th April 2021.

For more, see [Jenny Bryan's amazing presentation on naming things](https://speakerdeck.com/jennybc/how-to-name-files).

You may come up with better ways to name and keep track of files.
Remember the FAIR principles: organize the files so you can find them, access them, interoperate with other pieces of data, and generally reuse the data.


# Guidelines for electronic lab notebook entries and organization.

We use electronic lab notebooks made by [ResearchSpace a.k.a. RSpace	](https://www.researchspace.com/).
[Edinburgh instance of RSpace (password protected)](https://rspace.is.ed.ac.uk/).
You should have access set up via your EASE login, see [newstart](newstart).

Our lab notebooks are open, everyone in the lab can see everyone else's pages by default.
If someone wants to repeat one of your experiments, you should be able to share the lab notebook entry with them immediately.

We have work to do to making clearer instructions/guidelines for the use of RSpace:
- set up templates for common lab book entries.
- including, set a template for the annual lab book calendar.
- use tags to connect experiments with related features (protocols, reagents, strains, etc) 
- explain integration with protocols.io
- work on integration with github
- policy for when to sign entries?

Please ask Edward or Rosey for help on these issues.

To be continued...

## Have two kinds of tables of contents, one by date and one by project

We have found it seriously helpful to have one table of contents of activity by date, and another by project. That way you can search either by when it happened or by what it connects to, helping with the principle "Place your work in the context of larger goals and projects.". 

The table of contents by date works best if you:
- have a new entry for each calendar year e.g. called "Experiment Diary 2021".
- format as a table including hyperlinks to the individual notebook entries, so you can click straight through.
- have about one page per week in the lab, or more broken up if that's more helpful
- update frequently (e.g. weekly) so it's not all backed up.

We still need to make a template for this!

It is also helpful to have a table of contents by project, or for each project
- summarizing the overall aims of the project.
- breaking down into smaller aims, linked to the individual notebook pages working on those aims.
- include progress updates
- include dead ends and other things that were tried and learned from related to the project.

These are guidelines - take a look at how others organize their lab notebook, and find something that works for you.


# Principles for dry / computational lab notebooks

The same *principles* of keeping good records apply for computational/dry work, but the approach can differ.
Dry-only folk tend to use git/github rather than RSpace, and in general the guidelines are less clear.
For example, for computational projects like [riboviz](https://github.com/riboviz/riboviz) and [tidyqpcr](https://github.com/ewallace/tidyqpcr), the github repository for that project and its commit history also serves as a record of who did what when.

However a project-specific repository does not serve as a "work diary" in the way that a well-kept lab notebook does.
Ultimately you have to find your own approach - the PI is happy to discuss ideas here.
There are some nice ideas in [Ten Simple Rules for a Computational Biologist’s Laboratory Notebook](https://doi.org/10.1371/journal.pcbi.1004385)

To be continued...
