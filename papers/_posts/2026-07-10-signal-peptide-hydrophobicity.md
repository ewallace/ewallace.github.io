---
layout: paper
title: "Protein secretion routes in fungi are predicted by the length of the hydrophobic helix in the signal sequence"
year: "2026"
shortref: "Sones-Dykes and Wallace <i>G3</i> 2026"
nickname: signal-peptide-hydrophobicity
journal: "G3: Genes, Genomes, Genetics"
volume: 
issue:
pages: 
authors: "Sones-Dykes T, Wallace EWJ"
image: /assets/images/papers/secretion_pathways_schematic.svg
redirect_from: 
fulltext: https://doi.org/10.1093/g3journal/jkag134
pdflink: https://www.biorxiv.org/content/10.1101/2025.07.30.667231v1.full.pdf+html
github: https://github.com/TristanSones-Dykes/TMSP_Pub/
pmid: 42429560
pmcid: 
f1000: 
doi: "10.1093/g3journal/jkag134"
dryad_doi:
figshare_doi: 
zenodo_doi: "10.5281/zenodo.19801296"
altmetric_id:
category: paper
# Note: 'published' is a Jekyll keyword and does not refer to whether the paper is published, but rather to whether this Markdown should be part of the rendered site.
published: true
preprint: true
embargo: false	
peerreview: true
review: false
tags: [signal peptides, secreted proteins, translocon, fungi]
---
{% include JB/setup %}

# Abstract 

Secreted proteins are translocated across membranes through multiple routes. In eukaryotes, secreted proteins with N-terminal signal sequences can use either the signal recognition particle and its receptor or the alternative Sec complex to cross the endoplasmic reticulum membrane. Large-scale experiments on the substrates of these pathways are primarily from the model yeast *Saccharomyces cerevisiae*, but less is known about conservation of translocation pathways. Here, we take a computational approach to analyze secretion signals across the fungal kingdom. Computational predictions by the Phobius model separate secreted proteins in diverse fungal species into distinct populations: cleaved signal peptides with short hydrophobic helices of 8 to 13 amino acids and transmembrane proteins with long hydrophobic helices of 16 to 27 amino acids, similarly to *S. cerevisiae*. These computational predictions also robustly distinguish translocation routes in *S. cerevisiae*: Sec-dependent translocation of native proteins is accurately predicted by the presence of a cleaved signal peptide, while conversely signal recognition particle–dependent translocation is predicted by a retained signal-anchor. Analysis of multiple hydrophobicity scales and signal peptide prediction algorithms shows that the Phobius-predicted length of the hydrophobic helix alone is an effective predictor of translocation route. Our results support the hypothesis that the Sec complex is critical for cell wall biogenesis and protein secretion across fungi.


# Lay Summary

Fungal cells have their “stomachs on the outside” – they secrete proteins to the environment that act as enzymes that digest macromolecules, as well as importers of nutrients back across the cell membrane. For fungi that cause infections, the environment is the infected host animal, plant, or other fungus. Fungal cells are also protected by a cell wall, built by proteins that are secreted across the cell membrane and other proteins that use the cell’s secretory system and are then retained in the membrane. These secreted proteins are translocated across membranes by cellular machinery called translocons, and different secreted proteins use different translocons. Detailed studies of translocons in brewers’ yeast (*Saccharomyces cerevisiae*) identified the features in secreted proteins that determine which translocon they use. Specifically, there is a “signal sequence” near the start of secreted proteins; the features of this signal sequence direct the protein through the matched translocon. Because these translocons differ between yeast and animals, we asked if the signal sequences that direct secretion have similar properties in diverse fungi, including pathogens of humans, amphibians, and plants. Indeed, our computational predictions separate signal sequences into 2 clear groups that differ by a key feature, their hydrophobic helix.  We show that the length of this hydrophobic helix, not necessarily its maximum hydrophobicity, matters most to direct protein secretion in fungal cells: shorter helices use a translocon including the Sec63 component, and longer helices use a translocon involving the “Signal Recognition Particle”. The conservation of short helices in cleaved signal peptides across fungi is consistent with their use of the Sec complex and not the Signal Recognition Particle pathway, which merits further investigation. Secreted proteins with cleaved signal peptides, that likely use the Sec complex, include cell wall proteins, digestive enzymes, and “effectors” that manipulate the infected host to promote fungal infections.

## Note

This paper was previously [preprinted on bioRxiv](https://doi.org/10.1101/2025.07.30.667231), and publicly reviewed via Review Commons.