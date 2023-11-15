# Chem_154_Lab2_bioinfo

Author: Lance Anthony Aquino 

Date created: June 4, 2023

# Description:

Analysis done in Mol* and in-house jupyter notebook scripts, for examining specific residues of the Twort Group I Ribozyme sequence (Accession # AY954970.1, Nucleotide numbers 16983-17234)
and aligned sequences found in evolutionarily related bacteriophages.

# /molstar_save_states/:

Mol* analysis of the structure of the crystalized Twort Group I Ribozyme (Golden et al. 2004), with certain domains highlighted.
Note: Truncated P1 sequence and mutation U10A.

# /pairwise_alignment_tool/:

lab2_final.ipynb: Reads slightly modified .txt clustal outputs from several different pairwise alignments, that
contain the 252-nucleotide Twort ribozyme sequence aligned with a BLAST sequence from a 
given genome of select bacteriophages, and aligns the sequence, starting from the 
first chosen nucleotide alignment relative to the given Twort sequence, and ending
at the second chosen nucleotide alignment. Includes specific sequences examined
during the assignment, as well as an option for user input

# Accession numbers of sequences used:
- Staphylococcus phage Twort (Accession # AY954970.1) (Kwan, T., Liu, J., DuBow,M., Gros,P. and Pelletier, J. 2005)
- Herelleviridae (Accession #BK053323.1) ( Tisza,M.J. and Buck,C.B. 2021)
- Caudoviricetes (Accession # BK044123.1) ( Tisza,M.J. and Buck,C.B. 2021)  
- Siphoviridae (Accession # BK031186.1) (Tisza,M.J. and Buck,C.B. 2021)  
- Roseobacter phage CRP-7 (Accession # MK613349.1) (Zhang,Z.F., Chen,F., Chu,X., Zhang,H., Luo,H.W., Zhai,Z.Q., Yang,M.Y. and Zhao,Y.L. 2019), 
- Vibrio phage VPMCC14 (Accession #ON922990.1) (Kar,P. and Ghosh,K. 2022) 

# Other Software used:
- BLASTn (Query of alignments or potential Group I ribozyme sequences in other bacteriophage species)
- Clustal Omega (Outputs pairwise alignment files between Twort and candidate ribozyme sequences found in other bacteriophages)
- Jupyter Notebook Version 6.5.2 
- Mol* (https://molstar.org/)
