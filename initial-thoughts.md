---
title: "Genome Browsers: Introduction to visualization of genomic data-sets"
author: "Mark Dunning"
date: "25/09/2014"
output: html_document
---



1.  GRCh38 reference genome assembly: what's new?

2.  Intro to common file formats
  + Fasta, Fastq, SAM, BAM
  + BED, Wig, GFF, GTF
  + Biged, BigWig
  + VCF, PSL
  
3.  Introduction to Genome Browsers
  + Ensembl; configuring and navigating tracks on browser; how to make use of the new regulation track
  
  + Biomart: web access to genomic annotation
  
  + UCSC; configuring and navigating tracks on browser; table browser; data export to galaxy and genomespace
  
  + Mauve; syntenic regions; deletions, rearrangements, translocations
  
  + Tablet; visualize sequence reads, SNPs, BAM files etc.
  
  + DAS Distributed annotation systems
  
  + IGV; visualize sequence datasets; igvtools-how to format sequence data for IGV; (Bedtools/GenomeSpace/GiTools); Configure custom data server and custom genome (cancer genome and snp chip etc); How to build sample information files and annotated sessions; Gene list views; Shashi plots and junction bedfiles; shRNA output in the browser.; Creating dynamic tables and links to control IGV (tracktables package?); Sorting/controlling data using regions of interest (e.g. Diffbind DB peaks); how to configure an external distribution annotation systems for IGV

  + VISTA; tools for multi species genome visualization; identify conserved regions
  
  + CGview; circular genomes
  
  + Savant; SNPs and rearrangements
  
  
4.  Extraction and Visualization of genomic data using Bioconductor/R 
  + Rtracklayer
  + biomaRt
  + GViz
  + tracktables/ngsplot