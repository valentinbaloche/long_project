# Graph construction of SNPs data

Salmonella is among the most common foodborne pathogens worldwide, and can lead to acute gastroenteritis. The outbreaks involving this pathogen must be quickly identified. For this purpose, genome matching methods based on whole genome sequencing have been developed. The best known methods use phylogenetic trees based on the comparison of single nucleotide polymorphisms (SNPs). Today, methods that use this process involve three steps:

1-Mapping of reads on the reference genome (BWA, Bowtie, etc.)</br>
2-Search for SNPs (GATK, Freebayes, etc.)</br>
2-Use of these SNPs to infer a phylogenetic tree (IQTREE, RaXML, phyML, etc.)</br>

In epidemic case studies, relationships between strains are sought. Thus, it is not necessary to trace the entire evolutionary history of the strains. Moreover, this method takes a considerable amount of computing time. 

**The goal of this project is therefore to replace the 3rd step by the development of a graph-based method, which would save computation time and preserve the information provided by SNPs.
The main part of the development will use supervisor’s data with epidemiological links. These datasets consist of concatenated SNPs isolated from different strains of S. Typhimurium or its monophasic variant S. 1,4,5,12:i:-. The term ‘monophasic’ characterizes the position of the flagella present on only one side of the bacterium, as opposed to the other strains which have flagella on two poles.
The second part of the study will focus on the method’s effectiveness, in particular by carrying out tests on other datasets, including one with no related annotated strains.**


*[1]	L. Bonifait, A. Thépault, L. Baugé, S. Rouxel, F. Le Gall, et M. Chemaly, « Occurrence of Salmonella in the Cattle Production in France », Microorganisms, vol. 9, no 4, p. 872, avr.2021, doi: 10.3390/microorganisms9040872.*
