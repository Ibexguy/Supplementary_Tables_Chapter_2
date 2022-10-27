# Supplementary_Tables_Chapter_2
Supplementary Tables S1-S3 for the PhD-Thesis: Genetics of Bottlenecked Species Through Time: Insights from Ancient Genomes of the Alpine ibex by Mathieu Robin

## Table S1
Raw data statistics for samples included in the PSMC analysis. All calculations have been performed with samtools coverage. Sample describes the Sample ID. Start Position and End Position describe the range of positions which have been analysed, Number of Reads are the number of reads aligned to the corresponding region (after filtering), Covered Bases are bases with a depth >=1, Coverage [%] is the proportion of covered bases, Mean Depth describes the mean depth of coverage, Mean Base Quality describes the mean base quality score in covered region and Mean Mapping Quality describes the mean mapping quality in selected reads.

## Table S2
Overview of all samples used for this study including previously published data. 
### General sampling information: 
Shown are sampling state (sequencing was successful or not), Species, Age mentioned in Source (age as reported from the finder or the museums respectively), Age groups of the samples which are either ancient (1302 ± 26 BCE to 6601 ± 33 BCE) , historic (1919 CE to 1695 CE) or recent specimens, Dating Method (C14-Dating or museum entries), Object (sample material and body part), Inventory number (identification number supplied from the Donor), Country of Origin (where the specimen had presumably lived), Latitude and Longitude (individual sampling location in WGS84 format). 
### Sampling map information: 
Latitude_WGS84_centered and Longitude_WGS84_centered describe the coordinates samples in WGS84 format. Coordinates for specimens which originate from the same population have been centred by assigning a common coordinate. Location describes the different sampling groups, where we group spatially along the main Alpine divide and temporarily into ancient (1302 ± 26 BCE to 6601 ± 33 BCE, historic (1919 CE to 1695 CE), recent and temporary unknown samples. One sample, Zue2, had an exact finding date but had no location of origin. 
### Mapping statistics: 
Mean mitogenome coverage was calculated with samtools depth  when mapping to the Alpine ibex mitogenome (NC_020623.1). All following statistics are based on the mapping to the domestic goat reference genome (ARS1, (Bickhart et al. 2017)) and were calculated using samtools flagstats on the deduplicated bam files. Endogenous DNA [%] is defined as the percentage of all reads (after trimming), which mapped to the reference genome (here ARS1). Duplicates describes the absolute number of duplicated reads and Duplicates [%] the percentage of duplicate reads measured as percentage of the total number of reads. 
Statistics for the datasets Capra_ibex and Capra_all: summary statistics per individual for each of the two SNP datasets used in this study. 
