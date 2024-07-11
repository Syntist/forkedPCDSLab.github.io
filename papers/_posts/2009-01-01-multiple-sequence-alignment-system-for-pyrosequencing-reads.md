---
layout: paper
title: "Multiple sequence alignment system for pyrosequencing reads"
nickname: 2009-01-01-multiple-sequence-alignment-system-for-pyrosequencing-reads
authors: "Saeed, Fahad; Khokhar, Ashfaq; Zagordi, Osvaldo; Beerenwinkel, Niko; "
year: "2009"
journal: "Springer Berlin Heidelberg Bioinformatics and Computational Biology: First International Conference, BICoB 2009, New Orleans, LA, USA, April 8-10, 2009. Proceedings"
volume: 
issue:
pages: 362-375
is_published: True
image: /assets/images/papers/springer.png
projects: []
tags: []

# Text
fulltext:
pdf:
pdflink:
pmcid:
preprint: 
supplement:

# Links
doi: "10.1007/978-3-642-00727-9_34"
pmid:

# Data and code
github: []
neurovault:
openneuro: []
figshare:
figshare_names:
osf:
---
{% include JB/setup %}

# Abstract

Pyrosequencing is among the emerging sequencing techniques, capable of generating upto 100,000 overlapping reads in a single run. This technique is much faster and cheaper than the existing state of the art sequencing technique such as Sanger. However, the reads generated by pyrosequencing are short in size and contain numerous errors. In order to use these reads for any subsequent analysis, the reads must be aligned . Existing multiple sequence alignment methods cannot be used as they do not take into account the specific positions of the sequences with respect to the genome, and are highly inefficient for large number of sequences. Therefore, the common practice has been to use either simple pairwise alignment despite its poor accuracy for error prone pyroreads, or use computationally expensive techniques based on sequential gap propagation. In this paper, we develop a …