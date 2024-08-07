# Dynamic MF2A
Code for the paper "Dynamic mixture of finite mixtures of factor analysers with automatic inference on the number of clusters and factors" by M. Grushanina and S. Frühwirth-Schnatter arXiv:2307.07045, 2023

## DynMF2A_main_code.R
--> R code to run the Gibbs sampler algorithm for the dynamic mixture of finite mixtures of factor analysers model

## DynMF2A_convergence.R
--> R code to check the algorithm convergence

## DynMF2A_postprocessing.R
--> R code for the post processing of the MCMC draws which resulted from running DynMF2A_main_code.R, i.e. solving lable switching. calculating partition, ARI, error rate, number of factors in each cluster, cluster covariance matrices and their MSE

## DynMF2A_identification.R
--> R code for sloving rotation invariance of cluster-specific factor loaing matries (uses MatchAlign algorithm available in the R package "infinitefactor" and GLT rptation procedure available in the R package "econometric.factor.identification"

## Simulations_data.R
--> R code to reproduce simulated data sets

## real_data.R
--> R code to generate benchmark data sets
