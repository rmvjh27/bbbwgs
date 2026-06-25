## **Results**

Alignment of sample genomes to the reference and variant identification indicate the presence of two components comprising the *S*. Typhimurium genome, namely a bacterial chromosome and the pSLT plasmid. The effective lengths of the chromosome and pSLT based on variant annotation are 4.857 Mb and 93.933 kb, respectively. Accession SRR38876376 has the most chromosomal variants and plasmid variants compared to other genomes. The number of variants and variant rate of each sample are shown in Figure 1. Samples lacking pSLT data have low-depth reads for this plasmid.

***Figure 1 Number and rate of variants across *S*. Typhimurium genomes***
<img src="https://github.com/rmvjh27/bbbwgs/blob/341417ce13017b54919b50a773588eb8e2f75fe0/results/miniproject_table1.png" alt="fig1" width="500" height="175"/>

Single-nucleotide polymorphisms (SNPs) are the most numerous variants across all genomes, followed by multiple-nucleotide polymorphisms (MNPs). The most common effect exhibited by these SNPs are downstream and upstream gene variants, followed by synonymous, missense, and intergenic variants. Other variants such as frameshift, non-coding transcript exon, start/stop codon gain or loss, and inframe indel variants are less common. Figure 2 shows the log-transformed number of variants for each variant type across all genomes, and Figure 3 visualizes the number of each SNP effect for each genome.

***Figure 2 Log-transformed variant frequencies for each variant type per genome***
<img src="https://github.com/rmvjh27/bbbwgs/blob/341417ce13017b54919b50a773588eb8e2f75fe0/results/mini_project_fig2.png" alt="fig2" width="500" height="300"/>

***Figure 3 Number of SNP effects sorted by effect type for each genome: A) SRR39099216; B) SRR38876376; C) SRR38895580; D) ERR023773; E) SRR10178266; F) SRR38943380***

![fig3](https://github.com/rmvjh27/bbbwgs/blob/e450ad0e0770908949d6078fca9b743349bb12d5/results/fig3_snpEff.png)

A total of 41 genes with high-impact variants across all genomes were successfully mapped to UniProtKB entries of their protein products. Among these genes, sodium ion transport and DNA-templated transcription are the most numerous gene ontologies across all genomes, followed by regulation of single-species biofilm formation, defense response to virus, and oligosaccharide catabolic process (Figure 4). All genomes have variants of *oadA* and *ydiV* compared to the reference, while genomes SRR39099216 and ERR023773 have variants for *artJ* and *macB*. Genomes SRR38895580 and ERR023773 have variants for *lpfD*, *treC*, *ybfE*, and *ygbE*. Only genomes SRR38876376 and SRR38943380 have variants for *nanH* (Figure 5).

***Figure 4 Gene ontologies with more than 1 instance among all genomes***
<img src="https://github.com/rmvjh27/bbbwgs/blob/e450ad0e0770908949d6078fca9b743349bb12d5/results/mini_project_fig4.png" alt="fig4" width="700" height="500"/>

***Figure 5 Heatmap of high-impact gene variants in each genome. Each blue cell denotes the presence of variants of a gene (y-axis) in the corresponding genome (x-axis).***

![figure5](https://github.com/rmvjh27/bbbwgs/blob/e450ad0e0770908949d6078fca9b743349bb12d5/results/high_impact_genes.png)

Variants for *bcsG*, *dmsD*, *fepE*, and *mdtK* are only present in genome SRR39099216. Genome SRR38876376 has most unique gene variants compared to other genomes. Genome SRR10178266 has the least number of genes with variants, *dinB*, *sbmA*, *sseL*, and *ygdG* variants exclusively present in this genome, followed by genome SRR38943380 with variants for *bisC*, *ftsX*, *phsC*, and *ydiN*. Variants for *iaaA*, *phoE*, *steC*, and *ydiF* are exclusive to genome SRR38895580, while genome ERR023773 is characterized by variants for *patA*, *phnT*, *prfB*, *trmL*, and *yajI*.
