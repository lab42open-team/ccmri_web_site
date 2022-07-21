---
title: Tasks
layout: single
permalink: /tasks/full_text_tasks
<!-- sidebar:
  nav: "tasks" -->
---

## Text mining (WP1)
The main principle that governs PREGO is the extraction, significance-quantification, storing, and presentation of *process-environment-organism* associations. 
This task aims at answering the what **process**, which **environment**, which **organism** question by mining pertinent associations buried as free text in the scientific literature and public biological data. This work package comprises a range of tasks both sensu stricto text mining, and auxiliary tasks such as knowledge modeling (evaluation/enrichment of ENVO’s «environmental system process». 

### Objectives
* to extract *process-environment-organism* associations buried in the scientific literature, free text descriptions of biological database records, and in dedicated community web pages
* to develop a named entity recognition module to identify environmental process mentions in text


## Knowledge gathering and association extraction (WP2)
Main objective of this WP is to collect evidence such as: 1. manually curated sequence/specimen metadata, 2. expert validated sequence analysis predictions and 3. functionality predictionsby molecular ecology annotation pipelines from public biological data repositories and extract *process-environment-organism* associations. To each association a **level of-trust score** based on the evidence type, such as expert curation, validated automatic annotation, non-validated automatic annotation. 

### Objectives
* to collect *process-environment-organism* evidence from public data record metadata and computational analysis record annotations
* to assign a confidence score to each annotation based on its evidence source


## Homology-based annotation transfer (WP3)
WP3 aims to transfer sequence-attached annotations to novel sequences and sequences lacking metadata. Sequence similarity searches against an *ad hoc* PREGO sequence annotation database provide the vehicle to such *in silico* predictions. 

During software development, priority will be given on associating nonannotated marker genes (i.e. organism-specific genes) to processes and environments. Prior team experience and infrastructure from the SEQENV [15] project will be crucial to this end.

For each predicted annotation-transfer a statistical scheme will weigh both the annotation source (ie. text mining or databases), and the sequence-similarity match score. Such composite will quantify the association confidence.

Beyond homology-based annotation transfer, the ad hoc PREGO sequence annotation database and the similarity search components will also server WP5 (Association presentation). In particular, they will support sequence-based queries for PREGO users that would like to explore process-environmentorganism associations of sequences highly similar their in-house ones.

### Objectives
* to predict process and environment associations for novel sequences and/or sequences with insufficient metadata
* to establish a pipeline capable of supporting sequence-based searches to the PREGO platform


## Association unification (WP4)
This is a nexus work package at both scientific and technical aspects of the PREGO project. 

On the one hand WP4 aims to unify the associations produced by the three previous WPs. It does so by merging duplicates and by assigning an overall confidence score, a derivative of the constituent confidence scores weighted according to a scheme of scientific-evidence trust.

On the other hand it stores computed associations in a database. This facilitates the association sharing, search, and graph based visualization of the WP5. Also on a technical perspective a main responsibility of this WP is to **bridge the components and protocols followed by WP1 to WP3** to retrieve and analyze public text and sequence data. A **periodic update module** will be compiled to coordinate the rerun of PREGO’s data cycle and the enrichment of PREGO’s database with novel associations, as well as the readjustment of the confidence of existing ones (in the light of new scientific evidence).

To render PREGO viable beyond the duration of this call it is crucial it liaises with emerging data infrastructures (e.g. ELIXIR, LifeWatch, DataOne). 

### Objectives
* to unify the calculated process-environment-organism associations
* to devise an overall confidence scoring scheme for the PREGO associations
* to manage and store the unified associations in a database
* to support the periodic update of the PREGO associations and liaison to emerging data infrastructures


## Association presentation (WP5)
PREGO is an *end-user* oriented platform. Its users range from researchers with standard browsing information technology skills, to advanced users, such as web and bioinformatics pipeline developers.
“Virtual users”, like e-infrastructure data harvesting modules, are also included. WP5 is PREGO’s association presentation WP, i.e. PREGO’s “window” to its users.

### Objectives
* to make PREGO accessible to researchers via a web platform
* to support text and sequence searches to the PREGO process-environment-organism associations
* to present the confidence and supporting evidence of retrieved associations
* to present process-environment-organism associations as networks
* to facilitate network enrichment analysis and support function exploration
* to provide developers and data analysis with programmatic access and bulk download options

## Project management (WP6)
PREGO follows a simple organizational structure. The principal investigator and the to-be-recruited PhD/MSc students constitute the core of the project. Key for the project success are the external collaborators that can offer both scientific experience, as well as technical support. 

HCMR-IMBBC collaborators can contribute genomics, metagenomics and proteomics data to develop and evaluate PREGO with. Aim of this WP is orchestrate the communication among all aforementioned team members, establish the required technical infrastructure (server, document and dataset sharing), and monitor the project activities and progress. 

### Objectives
* To establish the PREGO team and to purchase and install the PREGO dedicated server
* To organize a hands-on meeting to establish the scientific and technical frameworks of the project
* To monitor, log, and coordinate the project's activities
* To link to a network of collaborations in academia and private companies to seek future funding

## Dissemination, publication, training and outreach (WP7)
The proposed project has strong communication, educational and collaboration perspectives. WP7 aims at organizing these so as to maximize knowledge gain starting from the PREGO team it self, and extending to HCMR-IMBBC and national collaborators, up to the pertinent scientific community.

### Objectives
* To maintain a blog and social media spreading the word on PREGO aim, progress and activities
* To submit PREGO open access publications
* To present PREGO at an international bioinformatics, biodiversity informatics workshop
* To teach PREGO and its underlying methodologies to local collaborators, bioinformatics course modules, and to national data infrastructure training activities
