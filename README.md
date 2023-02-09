# MarineGEO_HK
MarineGEO_HK working analyses



Multistep data processing included:
0_Raw sequence data are availible on figshare at doi: ####

1_RemoveAdaptors - use cutadapt in commandline to gunzip and trim F/R adapters

2_FilterAndTrim - use dada2 for quality control, filtering and chimera removal

3_AATranslation - use MACSE for alignment and protein translation and to remove seqs with nonsense AA

4_AssignTaxonomy - Use Qiime2 for identity clustering and taxonomic assignments. Need a formatted database

5_FiguresAndStats - use R to look for data analysis importing ASV table and taxa tables. Run stats and make coarse figures

data - ASV and taxa tables.
