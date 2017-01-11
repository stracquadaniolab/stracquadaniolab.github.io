---
layout: default
title: Research
---
The availability of high-throughput genomics data and the rapid development of synthetic biology techniques are changing the way we generate and test hypotheses on cellular functions and disease. Our research work focuses on developing algorithms to harness these technologies and answer fundamental biological and clinical questions.

##### Computational Synthetic biology
Recent advances in DNA synthesis technologies opened the path to engineer biological systems, from genes to pathways to entire eukaryotic genomes.  
We have been at the forefront in developing computational methods for synthetic genome engineering. We used our methods to build the synthetic yeast genome [(Sc2.0)](http://www.syntheticyeast.org), the first eukaryotic organism designed on a computer.  
We then used this *new* organism to identify minimal genomes compatible with life.
To do that, we developed algorithms to identify structural variation from deep-sequencing data, which allowed us to identify minimal genome patterns associated with wild-type fitness.  

![Biological Design Automation][bda_framework]

Our ultimate goal is to build biological systems at same pace we have been designing
electronic circuits for the past 30 years. Ironically, while there are groundbreaking advances in DNA synthesis and high-throughput screening platforms, current algorithms are not keeping up with the increasing design complexity of new synthetic constructs.
The lack of robust models to associate genotype to phenotype and
a shortage of optimisation methods to sample the combinatorial genomic space
represent the bottle-neck to automatic design of new biological systems.  
We are addressing these problems by designing phenotype prediction algorithms
based on deep learning and combinatorial evolutionary optimisation methods to design biological systems. Working together with biologists, we aim at
establishing a *design-build-test* framework for the rapid design and
synthesis of any biological system.

###### **Collaborations**
* [Joel S. Bader](http://www.baderzone.org), Johns Hopkins University, USA
* [Jef D. Boeke](http://www.med.nyu.edu/biosketch/boekej01), NYU Institute for Systems Genetics, USA

##### Biological network analysis
High-throughput sequencing technologies allowed us to discover hundreds of mutations associated with different diseases. Despite these findings, major challenges remain in translating these associations into clinical applications. Most cellular functions are accomplished by complex interactions among proteins, it is necessary to evaluate these mutations in the broader context of the human interactome.
We are developing data-fusion and network clustering algorithms that take advantage
of big biological datasets to generate testable hypotheses of disease susceptibility,
progression and outcome.  

![biological network analysis][bio_network_analysis]

We have shown that statistical enrichment methods are powerful tools to identify key networks in cancer. We are now developing methods to identify
statistically significant clusters of genes/proteins that associate with a
phenotype using multiple layers of information (i.e. RNA-seq, Mass-spec).
We are particularly interested in cancer, and specifically at changes in
angiogenic factors as a response to different treatments.

###### **Collaborations**
* [Francesco Pezzella](http://www.rdm.ox.ac.uk/principal-investigators/researcher/francesco-pezzella-2), University of Oxford, UK

##### Applied optimization
Designing efficient and robust systems often requires the solution of large scale optimization problems. Often, the objective function is expensive to evaluate, it is the output of a simulator or the derivatives are not available. Indeed, the objective function can be considered a "black-box", whose only known information being the input and the output.
We are interested in developing hybrid optimization methods aiming at efficiently solving
complex problems. We are particularly interested in
combining stochastic sampling methods (i.e. evolutionary algorithms) with
deterministic optimization methods with performance guarantee. We have been
successful in proposing a number of approaches to several optimization problems
in biology and industrial design, ranging from protein structure prediction to
electronic devices design.

###### **Collaborations**
* [Panos Pardalos](http://www.ise.ufl.edu/pardalos/), University of Florida, USA


[bda_framework]:/images/bda_framework.svg "Biological Design Automation"
[bio_network_analysis]:/images/bio_net_analysis.svg "Biological Network Analysis"
