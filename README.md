---
title: "omics OASIS by Jim Perry"
description: "MMAP is a comprehensive mixed model program for analysis of pedigree and population data."
---

<!-- This file provides the CONTENT for the OASIS website -->
<!-- javascript links are at the bottom of this file to improve page loading -->

<div class="toc-wrapper">
  <ol class="toc js-toc"></ol>
</div>

<p><a id="home" title="OASIS Introduction" class="toc-item"></a></p>

[**HOME**](/) &nbsp; &nbsp; [**Latest Release**](https://github.com/omicsOASIS/OASIS-releases-issues-Q-and-A/releases/latest){:target="_blank"} &nbsp; &nbsp; [**Issues and Q&A**](https://github.com/omicsOASIS/OASIS-releases-issues-Q-and-A/issues){:target="_blank"} &nbsp; &nbsp; [**OASIS Videos**](/videos.html)

## OASIS: Omics Analysis, Search and Information System

OASIS is an information system for analyzing, searching and visualizing associations between phenotypes, genotypes, and other types of omics data (such as transcriptomics, metabolomics, etc.).  It is designed to enable discovery by connecting to the thought processes of biological researchers in a way that allows them to search results from an initial GWAS (or other type of association study), ask follow up questions and get the answers in real-time.

OASIS accomplishes this with a web-based search system and a variety of real-time analysis tools including conditional & multi-covariates analysis, LD calculations, alternative data transformations, and customized SKAT analysis.  On-demand visualizations are provided in the form of boxplots, histograms, LocusZoom & Haploview plots. The OASIS search reports contain a broad spectrum of annotation from Annovar and WGSA plus a variety of links to external resources such as gnomAD, GTEx, HaploReg, Roadmap, UCSC and NCBI.  Because OASIS has a web-based user interface, an understanding of programming or the UNIX operating system is not required.

OASIS is powered by MMAP, a mixed model, genetic association software program written by Jeff O’Connell at the University of Maryland.  MMAP performs the real-time analysis options “behind the scenes”.  The OASIS user interface coordinates the use of MMAP’s unique options and algorithms to provide repeated, custom computations in a fraction of the time normally required. 

<p><a id="installation" title="Installation" class="toc-item"></a></p>

### Installation

OASIS installs on a Unix/Linux operating system running the Apache webserver.  The package requires Perl, R and MySQL. Auxillary programs, Haploview and Locuszoom, are optional.  Install them using the instructions from their websites. [Click here to download OASIS](https://github.com/omicsOASIS/OASIS-releases-issues-Q-and-A/releases/latest){:target="_blank"}.

---

<p align="center">OASIS: Omics Analysis Search and Information System - Copyright © 2017</p>
&nbsp;

<!-- And now for the javascript... -->
  <script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"></script>
  <script type="text/javascript" src="/assets/js_custom/application.js"></script>
