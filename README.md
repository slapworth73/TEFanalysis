# TEFanalysis

Conditions Processing Script includes script to (i) remove overlapping genes, (ii) removes genes longer than 1000nt,
(iii) assign annotations to genes transcriptional start sites and termination sites and (iv) only take genes that 
give a signal above the genome average

For (i), also have remove_overlapping script open
For (iii), chosen_annotations=harrys_annotations (you can replace harrys_annotations with annotations of your choice
For (iv), also have Find_ExpressingGenes open
Also have bin_data open

Paf1_Analysis and Spt4_Analysis:
Check what number the Index in line 38 assigns to each cluster. This will be required for future scripts

- Save the variables giving clusters for WT, mutant and TEFseq data. 
- Save the Index_WT and Index_WT_spt4 for use in Max Correlation Script
- Save the unbinned clusters for use in the Parameter Script
- Save the clusters of Fold Change Profile, Difference Profile, 
- Fold Change Reads and Difference Reads for use in Max Correlation Scripts
Save PAF1_TEFseq_NN and SPT4_TEFseq_NN for use in Max Correlation Scripts

Paf1 and Spt4 Parameter Analysis:
Using the unbinned clusters, input into Parameter Script.
X = the cluster you are extracting parameters for
Line 93 gives the best fit model and will need to be altered in the Parameter_Script Analysis accordingly. 

