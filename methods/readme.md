## **Methods**

Raw data of *S*. Typhimurium genomes sampled in the United States, United Kingdom, Germany, Malawi, China, and Mexico (accessions SRR39099216, SRR38876376, SRR38895580, ERR023773, SRR10178266, and SRR38943380 respectively) 
were downloaded from the NCBI SRA and assessed for quality using FastQC (Andrews et al. 2010). Adapters or low-quality reads were removed from the data using Fastp 
(Chen, Zhou, Chen & Gu 2018). The reads for each accession were then mapped to a S. Typhimurium reference genome with accession code GCF_000006945.2 in the NCBI Genome database using BWA (Li & Durbin 2010). 
The aligned reads were then converted into BAM files, sorted based on chromosome position, and indexed using SAMTools (Li et al. 2009). 

Variant calling was performed using FreeBayes (Garrison & Marth 2012) on aligned reads with minimum base quality of 20, minimum mapping quality of 20, and minimum depth of 10. Further removal of variants with quality scores 
below 30, depth values below 10, and occupy less than 10% of reads, or allele frequencies below, as well as normalization were performed using BCFTools (Danecek et al. 2021). The variants were then annotated using SnpEff 
(Cingolani 2012). The effects of the variants were then visualized by type using ngi_visualizations (https://github.com/NationalGenomicsInfrastructure/ngi_visualizations/). Genes with high-impact variants from each genome were 
then mapped to UniProtKB (Bateman et al. 2023) entries of their protein products for function identification via gene ontology and their presence in each genome was visualized as a Seaborn (Waskom 2021) heatmap.

*snpEff reports for each genome and UniProt ID mapping/gene ontologies are attached in this folder*
