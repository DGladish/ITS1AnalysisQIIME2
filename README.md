# ITS1AnalysisQIIME2
qiime2 bioinformatics pipeline for ITS region analysis for reads generated using the ITS1F primer

We seek to detect plant pathogens by the means of amplicon sequencing and metagenomics.
Here, we used Ion Torrent sequencing to generate the raw sequences.
Because we used the Fusion Primer library prep method, the ITS1 region was sequenced unidirectionally two times using primers ITS1F and ITS2R.

Ths script here will take you from a raw sequences from two separate runs (one run for the sequences generated using the ITS1F primer, one for the ITS2R primer) to an amplicon sequence variant (ASV) table with taxonomy lables. 
