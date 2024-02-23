# MarineGEO_HK
Data and code associated with pubilcation:
Shelby E. McIlroy, Isis Guibert, Anand Archana, Wing Yi Haze Chung, J. Emmett Duffy, Rinaldi Gotama, Jerome Hui, Nancy Knowlton, Matthieu Leray, Chris Meyer, Gianni Panagiotou, Gustav Paulay, Bayden Russell, Philip D Thompson, David M Baker (2024) Life goes on: spatial heterogeneity promotes biodiversity in an urbanized coastal marine ecosystem. Global Change Biology



Multistep data processing included:

0_Raw sequence data (fastq) for this project are availible on figshare at doi: 10.6084/m9.figshare.24862782 & 10.6084/m9.figshare.24862863

1_RemoveAdaptors - use cutadapt in commandline to gunzip and trim F/R adapters

2_FilterAndTrim - use dada2 for quality control, filtering and chimera removal

3_AATranslation - use MACSE for alignment and protein translation and to remove seqs with nonsense AA

4_AssignTaxonomy - Use Qiime2 for identity clustering and taxonomic assignments. Need a formatted database

5_FiguresAndStats - use R to look for data analysis importing ASV table and taxa tables. Run stats and make coarse figures

data - ASV and taxa tables.
