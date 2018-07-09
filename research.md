---
layout: default
title: Research
---
The availability of high-throughput genomics data and the rapid development of synthetic biology techniques are changing the way we generate and test hypotheses on cellular functions and disease. Our research work focuses on developing algorithms to harness these technologies and answer fundamental biological and clinical questions.

#### Synthetic genomics

##### Computer Aided Engineering (CAE) methods
Recent advances in DNA synthesis technologies opened the path to engineer biological systems, from genes to pathways to entire eukaryotic genomes. We have been at the forefront in developing Computer Aided Design (CAD) software for synthetic genome engineering, such as BioPartsBuilder [[Bioinformatics, 2016]](/publications#yang2015) and BioStudio [[Science, 2017]](/publications#Stracquadanio2017), which we used to build the first eukaryotic organism designed on a computer, the synthetic yeast [(Sc2.0)](http://www.syntheticyeast.org).

<!-- ![Biological Design Automation][bda_framework] -->

Our ultimate goal is to build biological systems at the same pace we have been designing
electronic circuits for the past 30 years. Ironically, while there are groundbreaking advances in DNA synthesis and high-throughput screening platforms, current algorithms are not keeping up with the increasing design complexity of new synthetic systems. The lack of robust models to associate genotype to phenotype and
a shortage of optimisation methods to sample the combinatorial genomic space
represent the bottle-neck to automatic design of new biological systems. We are addressing these problems by designing phenotype prediction algorithms
based on deep learning and combinatorial evolutionary optimisation methods to optimise biological systems recoding and assembly.

Working together with biologists, we aim at establishing a *design-build-test* framework for the rapid synthesis of any biological system.

##### Minimal genomes
Understanding the rules of life requires the identification of the building blocks supporting cellular life. At the genomic level, we are interested at the minimal set of genes required for cellular growth. As part of Sc2.0, we combined synthetic genomics and deep sequencing analysis to identify minimal genome patterns associated with wild-type fitness in yeast [[Genome Research, 2016]](/publications#stracquadanio2016).

We are now interested in scaling up synthetic genomics and sequencing analysis techniques to study minimal genomes of mammalian systems to understand the fundamental rules of cell growth and differentiation.

###### **Collaborations**
[Joel S. Bader](http://www.baderzone.org), Johns Hopkins University, USA; [Jef D. Boeke](http://www.med.nyu.edu/biosketch/boekej01), NYU Institute for Systems Genetics, USA; [Boyd McKew](https://www1.essex.ac.uk/bs/staff/profile.aspx?ID=1211), University of Essex, UK; [Panos Pardalos](http://www.ise.ufl.edu/pardalos/), University of Florida, USA.


#### Cancer biology

##### Genetics and genomics
Large scale cancer sequencing projects allowed us to explore the landscape of inherited and somatic mutations associated with cancer. To do that, we are taking a hierarchical approach putting these mutation into meaningful biological contexts, starting from genes up to pathways.

Using statistical learning, we characterised inherited pathways associated with increased cancer risks [[Nature Rev Cancer, 2016]](/publications#stracquadanio2016-nature) and inherited gene mutations associated with differential survival [[Clinical Cancer Research, 2016]](/publications#stracquadanio2016-ccr). We are now developing methods to analyse Genome Wide Association Studies (GWAS) at the gene and pathway level, and developing sequencing pipelines to identify rare mutations associated with relapse in multiple myeloma patients.

##### Pathway discovery
Most cellular functions are accomplished by complex interactions among proteins, it is necessary to evaluate cancer mutations in the broader context of the human interactome.
We are developing data-fusion and network clustering algorithms that take advantage
of big biological datasets to generate testable hypotheses of disease susceptibility,
progression and outcome.  

<!-- ![biological network analysis][bio_network_analysis] -->

We have shown that statistical enrichment methods are powerful tools to identify key networks in cancer. We are now developing methods to identify
statistically significant clusters of genes/proteins that associate with a
phenotype using multiple layers of information (i.e. RNA-seq, Mass-spectrometry).
We are studying angiogenesis and hypoxia as a response to different treatments.

###### **Collaborations**
[Francesco Pezzella](http://www.rdm.ox.ac.uk/principal-investigators/researcher/francesco-pezzella-2),  [Adrian Harris](https://www.oncology.ox.ac.uk/research/adrian-harris), [Benedikt Kessler](https://www.ndm.ox.ac.uk/principal-investigators/researcher/benedikt-kessler), University of Oxford, UK; [Roman Hajek](https://www.osu.eu/roman-hajek/57416/), University of Ostrava, Czech Republic.


<!-- ##### Applied optimization
Designing efficient and robust systems often requires the solution of large scale optimization problems. Often, the objective function is expensive to evaluate, it is the output of a simulator or the derivatives are not available. Indeed, the objective function can be considered a "black-box", whose only known information being the input and the output.
We are interested in developing hybrid optimization methods aiming at efficiently solving
complex problems. We are particularly interested in
combining stochastic sampling methods (i.e. evolutionary algorithms) with
deterministic optimization methods with performance guarantee. We have been
successful in proposing a number of approaches to several optimization problems
in biology and industrial design, ranging from protein structure prediction to
electronic devices design.

###### **Collaborations** -->


[bda_framework]:/images/bda_framework.svg "Biological Design Automation"
[bio_network_analysis]:/images/bio_net_analysis.svg "Biological Network Analysis"
