# Methods


Organism Sampling

Adult oysters (n=32) were obtained from three bays within Puget Sound, WA:  Fidalgo Bay (48°28'31.1"N 122°34'48.6"W), Dabob Bay (47°49'27.4"N 122°48'37.9"W), and Oyster Bay (47°06'21.2"N 123°04'32.8"W). Ctenidium tissue was removed and stored -80C. 


Sample Preparation and Sequencing

Sample preparation, library construction, and sequencing were performed by the Beijing Genomics Institute (BGI; Beijing, China). Isolation of DNA was by via the salting out method. Briefly, tissue was lysed with Proteinase K, followed by ethanol precipitation of nucleic acids. Sample DNA was examined for integrity via agarose gel (see Figure 2). Thirty-two samples from each population were selected for sequencing.

Library preparation was performed following the approach developed by \citet{Elshire_2011}. Oyster DNA and Illumina adapters containing barcodes were digested with ApeKI restriction enzyme (recognition site: GCWGC). Adapters were ligated to digested oyster DNA, with each individual oyster receiving a unique barcode. These libraries were pooled and subjected to polymerase chain reaction (PCR). Average insert size (219bp) was determined via Bioanalyzer (Agilent Technologies). This pool was sequenced on a HiSeq 4000 (Illumina) as an 100bp pair-end run. 

Bioinformatics


The Reseqtools software package (BGI; https://github.com/BGI-shenzhen/Reseqtools) was used to remove adaptor sequenes and low quality reads (reads with greater than 50% of bases with a Q value <= 5), and then demutliplexed using the split.sh script. The script utilizes the index.lst file for barcode identification and the enzyme.txt file for identifying the cut site used during library preparation (see Code Availability subsection for script files). Reads lacking barcodes were discarded. Read alignments were performed using the proprietary NPGT software packages (BGI; Beihing, China).

Single nucleotide polymorphisms (SNPs) were identfied using radsnp, a part of the NPGT software package. Loci lacking >50% of SNP data were filtered out and the remaining loci were used to generate a list of genoytpes.



Code Availability

The Reseqtools software package for demultiplexing can be found in this GitHub repository: https://github.com/BGI-shenzhen/Reseqtools. The split.sh script and the index.lst files are both available in a dedicated GitHub repository (https://github.com/kubu4/paper_oly_gbs/tree/master/data).

The NPGT software package used for SNP detection and gentoype determination is an in-house, proprietary package used by BGI and is not available for use.