# Diff_expression_analysis
This repository contain workflow for differential gene expression analysis using Cufflinks

We used STAR for genome indexing and alignment and Cufflinks software for differential gene expresion analysis. Detailed pipeline can be found in pipeline.txt. All procedures were performed on Google Cloud platform.

System requirements for used software:
1. STAR: 64-bit computer running either Linux or Mac OS X, minimum – CPUs=4, RAM=32Gb; recommended settings of Google Cloud VM – CPUs=8, RAM=130 Gb; recommended options for genome indexing: --sjdbOverhang 99 --genomeChrBinNbits 15
2. CuffLinks: minimum – 64-bit computer running either Linux or Mac OS X; 4 GB of RAM; recommended settings of Google Cloud VM – CPUs=8, RAM=52 Gb.
