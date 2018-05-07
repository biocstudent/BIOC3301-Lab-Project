BIOC3301 Soil Microbiome Lab Project

This repository contains all of the batch files which were used to carry out data analysis of the paired end sequence reads obtained following Illumina MiSeq sequencing of 16S rRNA V4 regions present in microbial gDNA extracted from soil samples obtained from several greenspaces in central London. All analyses were carried out on Cirrus, a high performance computer cluster which is based at the University of Edinburgh.

Raw Sequence Data Analysis: 

1. Join paired end reads - joined_paired_ends
2. Split libraries - demultiplexing and quality filtering - splitting_libraries
3. Counting sequences - count_seqs
4. Pick closed reference OTUs against the SILVA 128 reference database - pick_closed_reference
5. Summarise OTU table - biom_summarize_table
6. Core diversity analysis - core_diversity_analysis
7. Convert weighted 3D PCoA plots to 2D plots - convert_to_2d_PCoA_plots_weighted

Statistical Analysis:

1. Analysis of statistical significance of sample groupings using ANOSIM for: 
   - pH - compare_categories_weighted_pH
   - Nitrogen - compare_categories_weighted_nitrogen
   - Phosphurus - compare_categories_weighted_phosphorus
   - Potassium - compare_categories_weighted_potassiun
2. Summarise taxa table - summarize_taxa 
3. Group Significance for:
   - pH - group_significance_pH
   - Nitrogen - group_significance_nitrogen
   - Phosphorus - group_significance_phosphorus
   - Potassium - group_significance_potassium
