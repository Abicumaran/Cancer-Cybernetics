# Cancer-Cybernetics
Single-cell Data and Complex Networks Analysis Codes (Review paper in Biological Cybernetics)

The Dataset folder contains all PID Networks data (including the raw abundance matrix for MS proteomic profiling and CCLE Histone Mass spect.)
used in the study of pediatric cancer cell fate dynamics for a review paper in J. Biological Cybernetics (Springer). 

The gene expression count matrix from Neftel et al. 2019 (SCP393) can be found at the link provided in the word document 'Data and Codes', or at 
the following link: https://singlecell.broadinstitute.org/single_cell/study/SCP393/single-cell-rna-seq-of-adult-and-pediatric-glioblastoma#study-summary
Use the metadata to extract only the pediatric GBM samples to reproduce our analyses/results (N=1943 cells, n=8 patients).

The Codes and Instructions for the complex networks analyses and single-cell clustering/trajectory inference algorithms
are found in the 'Data and Codes' document. Note: the Bayesian GRN from the scRNA-Seq counts in Figure 2 was reconstructed
from Julia LightGraphs package, while all other networks were reconstructed in R using the igraph package. For instructions 
on using the LightGraphs package, refer to: https://github.com/Abicumaran/GBM_Complexity_I
