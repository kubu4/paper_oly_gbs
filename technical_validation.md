# Technical Validation

Input DNA quality was evaluated by agarose gel electrophoresis (Data Citation 1: https://osf.io/ndu34/; Data Citation 2: http://doi.org/10.17605/OSF.IO/J8RC2). All samples used for library construction were scored by BGI as "Level A", meaning the integrity of the input DNA was good and the amount of sample was sufficient for two or more library constructions.

All FASTQ sequencing data files (Data Citation 3: NCBI SRA SRP099079) were evaluated using FastQC (Andrews, 2010) to identify any potential anomalies. Overall, the FastQC analysis results were consistent with libraries generated from DNA subject to restriction digestion: they fail "Per base sequence content," "Sequence Duplication Levels," and "Kmer Content" tests. The reason for these failures is due to the presence of the ApeKI restriction site present on all reads and is the expected result from those aspects of the FastQC analysis.

