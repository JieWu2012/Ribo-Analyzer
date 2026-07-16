# Ribo-Analyzer

[![DOI](https://zenodo.org/badge/383824144.svg)](https://doi.org/10.5281/zenodo.15048364
        
        


This code is for calculating the relative codon occupancy in the analysis of ribosome profiling data. 

"Codon_occupancy_cal.sh" script acceptes the mapping results (SAM format) and sequence of CDS (Fasta format) as input and it outputs the occupancy of each codon. Make sure the CDS fasta file matches the reference you used to map the Ribo-seq reads.  And use the following command: 

Codon_occupancy_cal.sh hg38_CDS_example.fa Mapped.sam


## Citation

This repository contains the code used to analyze the data presented in the following paper:

Sharma, P., Wu, J., Nilges, B. S. & Leidel, S. A. (2021). [Humans and other commonly used model organisms are resistant to cycloheximide-mediated biases in ribosome profiling experiments](https://www.nature.com/articles/s41467-021-25411-y). *Nature Communications*, 12, 5094.
