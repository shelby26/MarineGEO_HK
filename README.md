# MarineGEO_HK
MarineGEO_HK working analyses



Multistep data processing included:
0_Raw sequence data

1_RemoveAdaptors - use cutadapt in commandline to gunzip and trim F/R adapters

2_dada2_quality control, filtering and chimera removal

3_MACSE_protein translation and non-sense removal

4_Database formatting

5_Qiime2 for identity clustering and taxonomic assignments

6_R for data analysis and tables and coarse figures
