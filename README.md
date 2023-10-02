# BILL2
Scripts for parsing a VCF file resulting from bcf-tools merge

The Jupyter Notebook contains scripts to parse a VCF file resulting from `bcftools merge`.
This script generates a simplified VCF file as TSV.

The issue with the TSV file generated is that it keeps structural variants at the same position.
We tried to correct this issue with a filter of 30 bp, it is optional right now.

The additional VCF file results from comparing tools

Input: a VCF file resulting from VCF-tools

Output: a TSV file containing info from the VCF
