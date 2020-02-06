# Diff_expression_analysis
This repository contain workflow for differential gene expression analysis using Cufflinks

We used STAR for genome indexing and alignment and Cufflinks software for differential gene expresion analysis. Detailed pipeline can be found in pipeline.txt. All procedures were performed on Google Cloud platform.

System requirements for used software:
1. STAR: 64-bit computer running either Linux or Mac OS X, minimum – CPUs=4, RAM=32Gb; recommended settings of Google Cloud VM – CPUs=8, RAM=130 Gb; recommended options for genome indexing: --sjdbOverhang 99 --genomeChrBinNbits 15
2. CuffLinks: minimum – 64-bit computer running either Linux or Mac OS X; 4 GB of RAM; recommended settings of Google Cloud VM – CPUs=8, RAM=52 Gb.

References
Dobin, A., and Thomas R. Gingeras. Mapping RNA‐seq reads with STAR. Current protocols in bioinformatics 51.1 (2015): 11-14. 
Trapnell, C., Roberts, A., Goff, L. et al. Differential gene and transcript expression analysis of RNA-seq experiments with TopHat and Cufflinks. Nat Protoc 7, 562–578 (2012). https://doi.org/10.1038/nprot.2012.016
