# NetTDP
Permutation-based Network True Discovery Proportions (NetTDP), is proposed to quantify the number of edges (correlations) or nodes (genes) for which the co-expression networks are different.In the NetTDP method, we propose an edge-level statistic and a node-level statistic, and detect true discoveries of edges and nodes in the sense of differential co-expression network, respectively, by the permutation-based sumSome method.

A demo is provided for user. Please install WGCNA and sumSome package first before running demo file.

#### WGCNA installation
#CRAN
install.packages("WGCNA")

#Bioconductor
install.packages("BiocManager") 
BiocManager::install("WGCNA")

#github
install.packages("devtools")
library(devtools)
install_github("cran/WGCNA")

#### sumSome installation
devtools::install_github("annavesely/sumSome")
