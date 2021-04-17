---
layout: post
title: "Lab notebook guidelines DRAFT"
description: "Guidelines for electronic lab notebook entries and organization"
about: true
author_handle: ew
tags: [labmanual, newstart]
---
{% include JB/setup %}

# Why lab notebooks are important

Good record-keeping is an essential part of good work:

* Your lab notebook helps you to remember what you did and why.
* Your lab notebook is the best way to communicate activity and data around the lab.
* Keeping good records is a legal and funder requirement.

The lab notebook is a legal requirement, and belongs to the institution, not to you personally.
Keeping it up to date is a responsibility to yourself, to our research group, and to the institution.

Some scenarios where good lab notebook entries are useful:

* You want to show your last month's data to the PI or a colleague.
* You need to repeat an experiment you last did a year ago.
* A new lab member is comparing two approaches to an experiment, their pros and cons.
* An experiment that used to work has stopped working, and we need to go over the details of reagents and what has changed.
* You are writing up the methods section of your PhD thesis or paper.
* The reviewers for your paper ask to see other items of raw data.

In all these cases, if you have kept good lab notebooks you and your colleagues will be grateful to past you.
If you have not kept good records, you and your colleagues will be annoyed with, and disappointed in, past you.
You might think you will remember the details, but you won't.
Without good notebooks, important points will be forgotten, your or someone else's time will be wasted, and you risk accusations of misconduct.

In summary, the lab notebook is a tool to do good work, that is practically useful for you.
Keeping your lab notebook up to date is a non-negotiable requirement for students and staff who work in the wet lab.

# Principles for lab notebooks

*Your experiment is not "done" until it is written up in your lab notebook.*

Your lab notebook should:

* Describe your substantial activities in the lab every day, with dates.
* Describe your work in enough detail to reproduce it.
* Include, or link to, every piece of substantial data that you collect.
* Place your work in the context of larger goals and projects.
* Be updated within a week.

It is helpful to consider the [FAIR principles for scientific data management](https://www.go-fair.org/fair-principles/), which also apply to protocols, anlaysis and methods.

* *Findable:* The first step in (re)using data and protocols is to find them. Your lab notebook entries should be findable by "metadata", for example project, protocol, strain or oligo identifier, or date of creation.
* *Accessible:* Once the user finds the required data you should be able to access it. So if the lab notebook entry mentions a dataset elsewhere (e.g. datastore, lab notebook page), link to it with accession information.
* *Interoperable:* The data usually need to be integrated with other data, and to interoperate with applications or workflows for analysis, storage, and processing. Use standard file formats.
* *Reusable:* The ultimate goal is to optimise the reuse of data, protocols, and methods. You and others should be able ot re-use qhat you have done, to a high standard, and efficiently.

Exactly how these principles are achieved is a matter of judgment.
You need to set aside both time and mental energy to write the lab notebook.
Good habits help templates for entries, regular time to update the notebook.

## Examples of what to include and what not

Basically everything that is easy and/or important to include in your lab notebook should be in there.
To inform the judgment call of what to include and what not:


* *Handwritten notes* are fine to include, just take a photo of it and paste in with enough metadata that you can find it again.
*
* *Plasmid minipreps*, should include the name and batch number of the kit you used, and an electronic copy of the nanodrop/DeNovix
*

## Raw unedited data must be included

Raw unedited data must be included or linked to, without exception. 
Usually larger files will be kept on datastore and linked to, see the section on datastore organization in  [the manual page on where data belongs](where-data-belongs).

For example:
* the unedited image file from the imagequant/scanner/tablet/camera. This would usually be in .tif format. See Claus Wilke's chapter on [understanding common image file formats](https://clauswilke.com/dataviz/image-file-formats.html)
* the .txt file of your nanodrop results
* the .xls file of the plate reader readings
* the .ixo and .txt files from a qPCR run
* the exported data from the fragment analyzer (check format)
* the .fastq file from your sequencing run should be placed on datastore and linked to from the relevant lab notebook page when you receive it back

We have tried to set up the lab to make this easy. 
Almost all instruments are linked to the internet and datastore, so that you can copy your data straight
Investing in the habits of efficient record keeping will pay off.

Quoting the [Leek lab's guide to sharing data]()

## Give your files good names

Ending the filename with a data in standard format `yyyy-mm-dd` means that you can unambiguously link the data to the day it is collected.
For example `Vlad-platereader-rbpmutants-replicate1-2021-04-15.xls` tells us that these are data from Vlad's plate reader experiment, on rbp mutants, replicate one, on the 15th April 2021.
Then it is easy to reunite with Vlad's lab notebook from 15th April 2021.

You may come up with better ways to name and keep track of files.
Remember the FAIR principles.


# Guidelines for electronic lab notebook entries and organization.

This document describes guidelines for use of electronic lab notebooks on [researchspace](https://www.researchspace.com/).
[Edinburgh instance of Rspace (password protected)](https://rspace.is.ed.ac.uk/)

We need to set up some templates.

To be continued...

## Principles for dry / computational lab notebooks

The same *principles* of keeping good records apply for computational/dry work, but the approach can differ.
Dry-only folk tend to use git/github rather than RSpace, and in general the guidelines are less clear. 
There are some nice ideas in [Ten Simple Rules for a Computational Biologist’s Laboratory Notebook](https://doi.org/10.1371/journal.pcbi.1004385)

To be continued...