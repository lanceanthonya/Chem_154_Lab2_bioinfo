# Chem_154_Lab2_bioinfo

Author: Cin Aquino 

Date created: June 4, 2023

/molstar_save_states/:
Mol* analysis of the crystalized Twort Group I Ribozyme (Golden et al. 2004), with certain domains highlighted.
Note: Truncated P1 sequence

/pairwise_alignment_tool/
Reads slightly modified .txt clustal outputs from several different pairwise alignments, that
contain the 252-nucleotide Twort ribozyme sequence aligned with a BLAST sequence from a 
given genome of select bacteriophages, and aligns the sequence, starting from the 
first nucleotide alignment relative to the given Twort sequence, and ending
at the second chosen nucleotide alignment.

Written for creating visualizations of alignments and %similarity in selected alignment regions
of the ribozyme sequence, as part of the final submitted lab report for Chem 154

Accession numbers of sequences used:
Herelleviridae (Accession #BK053323.1) ( Tisza,M.J. and Buck,C.B. 2021)
Caudoviricetes (Accession # BK044123.1) ( Tisza,M.J. and Buck,C.B. 2021)  
Siphoviridae (Accession # BK031186.1) (Tisza,M.J. and Buck,C.B. 2021)  
Roseobacter phage CRP-7 (Accession # MK613349.1) (Zhang,Z.F., Chen,F., Chu,X., Zhang,H., Luo,H.W., Zhai,Z.Q., Yang,M.Y. and Zhao,Y.L. 2019), 
Vibrio phage VPMCC14 (Accession #ON922990.1) (Kar,P. and Ghosh,K. 2022) 
Staphylococcus phage Twort (Accession # AY954970.1) (Kwan, T., Liu, J., DuBow,M., Gros,P. and Pelletier, J. 2005)

Other Software used:
BLASTn
Clustal Omega
Other in-house Jupyter notebook scripts
Mol* (https://molstar.org/)
