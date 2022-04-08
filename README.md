### Acrogenospora terricola

This contains sequence, alignment, and tree files from Harrington et al. 2022

The unaligned, untrimmed .fasta files for each locus are named "Acrogenospora_locus.fasta." The fullITS file is untrimmed and still contains partial SSU and/or LSU sequences at each end. They can be trimmed manually or ITSx can remove them. 

Sequences were aligned with mafft: "mafft --auto ~/path/input.fasta > ~/path/ITSx/input_aln.fasta"

The aligned input (.phylip), parameter, and CIPRES output files ('RAxML_bipartitions.result') for RAxML trees are in folders with their respective "locus_acro" as the names.

Note that I made some minor cosmetic changes from the RAxML outputs: I trimmed duplicated sequences that were initally included because they had different accession names (e.g., the formal name Acrogenospora_thailandica_MFLUCC_17_2396_T was kept and the strain name Acrogenospora_sp.JY_2018_MFLU_18_1129 removed), and I alterered the name for MFLU-18-1130 to match what I've seen used in other articles as there is some ambiguity over whether A. carmicheliana has nomenclatural priority over A. sphaerocephala, altered sequences called Farlowiella to Acrogenospora to reflect the current name. 
