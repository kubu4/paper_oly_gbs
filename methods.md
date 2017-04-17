# Methods


Organism Sampling and Nomenclature

Adult oysters (n=32) were obtained from three bays within Puget Sound, WA: Dabob Bay (47°49'27.4"N 122°48'37.9"W), Fidalgo Bay (48°28'31.1"N 122°34'48.6"W), and Oyster Bay (47°06'21.2"N 123°04'32.8"W). Ctenidium tissue was removed and stored -80C. Individuals from Dabob Bay were labeled 1HL_XXA, Fidalgo Bay were labeled 1NF_XXA, and Oyster Bay were labeled 1SN_XXA, where 'XX' is a unique identification number.


Sample Preparation and Sequencing

Sample preparation, library construction, and sequencing were performed by the Beijing Genomics Institute (BGI; Beijing, China). Isolation of DNA was by via the salting out method. Briefly, tissue was lysed with Proteinase K, followed by ethanol precipitation of nucleic acids. Sample DNA was examined for integrity via agarose gel (Data Citation NUMBER: https://osf.io/ndu34/; Data Citation 2: http://doi.org/10.17605/OSF.IO/J8RC2). Thirty-two samples from each population were selected for sequencing.

Library preparation was performed following the approach developed by \citet{Elshire_2011}. Oyster DNA and Illumina adapters containing barcodes were digested with ApeKI restriction enzyme (recognition site: GCWGC). Adapters were ligated to digested oyster DNA, with each individual oyster receiving a unique barcode. These libraries were pooled and subjected to polymerase chain reaction (PCR). Average insert size (219bp) was determined via Bioanalyzer (Agilent Technologies). This pool was sequenced on a HiSeq 4000 (Illumina) as an 100bp pair-end run. 

Bioinformatics

Single nucleotide polymorphisms (SNPs) were identfied using radsnp, a part of the NPGT software package. Loci lacking >50% of SNP data were filtered out and the remaining loci were used to generate a list of genoytpes.



Code Availability

The NPGT software package used for SNP detection and gentoype determination is an in-house, proprietary package used by BGI and is not available for use.
