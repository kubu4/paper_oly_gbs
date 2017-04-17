# Data Records

All FASTQ files corresponding to each individual oyster (192 files) have been deposited in the National Center for Biotechnology Information (NCBI) Sequence Read Archive (SRA). (Data Citation 1: NCBI SRA SRP099079). All FASTQ files were analyzed with FastQC. The output files from were grouped together by population and then compressed into three gzipped tarballs: oly_gbs_HL_fastqc.tar.gz, oly_gbs_NF_fastqc.tar.gz, oly_gbs_SN_fastqc.tar.gz (Data Citation 2:, Data Citation 3:, Data Citation 4:).

Other data files described in this manuscript are stored in a publicly available Open Science Framework repository: http://doi.org/10.17605/OSF.IO/J8RC2 (Data Citation 2: http://doi.org/10.17605/OSF.IO/J8RC2). These data are available under a Creative Commons Attribution 4.0 International Public License, whereby anyone may freely use and adapt the data, as long as the original source is credited, the original license is linked, and any changes to the data are indicated in subsequent use.

Beijing Genomics Institute provided a quality control (QC) report of the initial samples they received, as well as an evaluation of the subsequent DNA isolations they performed: 20160105_F15FTSUSAT0768_QC_Report.pdf (Data Citation 2: http://doi.org/10.17605/OSF.IO/J8RC2). The report includes agarose gel images of all samples to assess DNA integrity prior to library construction.

An overview of sequencing results is provided in the Data.stat.xls file (Data Citation 2: http://doi.org/10.17605/OSF.IO/J8RC2). This provides the read numbers (millions of bases), base numbers (megabases), GC percentage, Q20 percentage, and Q30 percentage for each sample sequenced. A summary of this data at the population level can be found in Table 1.

Genotyping information for all individuals is contained in the Genotype.xls file. This spreadsheet provides loci information for indvidual genotypes. Over 10,000 loci were identified (10,363) and used for uniquely genoytping individuals. Each row corresponds to an identified locus and has been assigned a unique ID. The Consensu_Seq column provides an 82 nucleotide region containing an individual SNP that is unique to at least one of the individuals. The position of this SNP within that 82 base region is indicated in the pos column. The subsequent columns represent each of the 96 individuals with the following nomenclature. The leading number and trailing letter are constants (i.e. are the same across all individuals). The first two letters indicate the population to which the individual belongs (HL - Daboby Bay; NF - Fidalgo Bay; SN - Oyster Bay). The two digit number following the underscore is a unique ID for that particular individual. An example of the nomenclature for Daboby Bay oyster #23: 1HL_23A.

Single nucleotide polymorphisms (SNPs) were identified in each individual. The total number of homozygous and heterozygous SNPs within each individual are documented in the SNP.stat.xls spreadsheet (Data Citation 2: http://doi.org/10.17605/OSF.IO/J8RC2). Additionally, this spreadsheet provides a percent contribution of homozygous and heterygous SNPs within each individual. At the population level, we determined the mean number of homozygous and heteroyzgous SNPs within each of the three populations, as well as the percent contributions of homozygous and heterozygous SNPs (Table 2).

#### Sequencing Data Summary Table (Table 1. put here for quick reference - needs to be separate figure)

|  Population  | Mean Reads (M) | Mean Base Number (Mb) | Mean GC (%) | Mean Q20 (%) | Mean Q30 (%) |
|------------|----------------|-----------------------|-------------|--------------|--------------|
| All        | 5.66           | 548.06                | 42.59       | 95.64        | 90.73        |
| Dabob Bay (HL) | 5.53           | 532.27                | 42.65       | 95.63        | 90.67        |
| Fidalgo Bay (NF)         | 5.52           | 538.66                | 42.54       | 95.66        | 90.78        |
| Oyster Bay (SN)         | 5.92           | 573.25                | 42.59       | 95.64        | 90.74        |
