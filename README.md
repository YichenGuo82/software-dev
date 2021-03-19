[![](https://raw.githubusercontent.com/USCbiostats/badges/master/tommy-image-badge.svg)](https://image.usc.edu)

Software Development Standards
================

This project’s main contents is located in the project’s
[Wiki](https://github.com/USCbiostats/CodingStandards/wiki):

## Coding Standards

1.  [Coding Standards](../../wiki/Home#coding-standards)
2.  [Software Thinking](../../wiki/Home#software-thinking)
3.  [Development Workflow](../../wiki/Home#development-workflow)
4.  [Misc](../../wiki/Home#misc)

We do have some direct guidelines developed as issue templates
[here](templates).

## Bioghost Server

1.  [Introduction](../../wiki/Biogohst-server#introduction)
2.  [Setup](../../wiki/Biogohst-server#setup)
3.  [Cheat Sheet](../../wiki/Biogohst-server#cheat-sheet)

## HPC in R

  - [Parallel computing in
    R](../../wiki/HPC-in-R#parallel-computing-in-r)  
  - [parallel](../../wiki/HPC-in-R#parallel)
  - [iterators+foreach](../../wiki/HPC-in-R#foreach)
  - [RcppArmadillo +
    OpenMP](../../wiki/HPC-in-R#rcpparmadillo-and-openmp)

# Happy Scientist Seminars

The Happy Scientist Seminars are educational seminars sponsored by Cores
C and D of the Biostats Program Project award. This series, the “Happy
Scientist” seminar series, is aimed at providing educational material
for members of Biostats, both students and faculty, about a variety of
tools and methods that might prove useful to them. If you have any
suggestions for subjects that you would like to learn about in future,
please send email to Paul Marjoram at (<pmarjora@usc.edu>). Our agenda
will be driven by your specific interests as far as is possible.

List of past seminars with material can be found
[here](/happy_scientist/).

# USCbiostats R packages

``` r
dat$Name <- sprintf("[**%s**](https://github.com/USCbiostats/%s)", dat$Name, dat$Name)
knitr::kable(dat, row.names = FALSE)
```

| Name                                                                      | Description                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| :------------------------------------------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [**AnnoQR**](https://github.com/USCbiostats/AnnoQR)                       | R client wrap for AnnoQ API (<https://github.com/blueOwl/AnnoQR>) [![CRAN status](https://www.r-pkg.org/badges/version/AnnoQR)](https://CRAN.R-project.org/package=AnnoQR) [![CRAN downloads](http://cranlogs.r-pkg.org/badges/grand-total/AnnoQR)](https://cran.r-project.org/package=AnnoQR) [![status](https://tinyverse.netlify.com/badge/AnnoQR)](https://CRAN.R-project.org/package=AnnoQR)                                                   |
| [**aphylo**](https://github.com/USCbiostats/aphylo)                       | Statistical inference of genetic functions in phylogenetic trees [![CRAN status](https://www.r-pkg.org/badges/version/aphylo)](https://CRAN.R-project.org/package=aphylo) [![CRAN downloads](http://cranlogs.r-pkg.org/badges/grand-total/aphylo)](https://cran.r-project.org/package=aphylo) [![status](https://tinyverse.netlify.com/badge/aphylo)](https://CRAN.R-project.org/package=aphylo)                                                    |
| [**bayesnetworks**](https://github.com/USCbiostats/bayesnetworks)         | C++ program to fit Bayesian networks, illustrated with simulated data [![CRAN status](https://www.r-pkg.org/badges/version/bayesnetworks)](https://CRAN.R-project.org/package=bayesnetworks) [![CRAN downloads](http://cranlogs.r-pkg.org/badges/grand-total/bayesnetworks)](https://cran.r-project.org/package=bayesnetworks) [![status](https://tinyverse.netlify.com/badge/bayesnetworks)](https://CRAN.R-project.org/package=bayesnetworks)     |
| [**BinaryDosage**](https://github.com/USCbiostats/BinaryDosage)           | Converts VCF files to a binary format [![CRAN status](https://www.r-pkg.org/badges/version/BinaryDosage)](https://CRAN.R-project.org/package=BinaryDosage) [![CRAN downloads](http://cranlogs.r-pkg.org/badges/grand-total/BinaryDosage)](https://cran.r-project.org/package=BinaryDosage) [![status](https://tinyverse.netlify.com/badge/BinaryDosage)](https://CRAN.R-project.org/package=BinaryDosage)                                           |
| [**causnet**](https://github.com/USCbiostats/causnet)                     | What the Package Does (One Line, Title Case) [![CRAN status](https://www.r-pkg.org/badges/version/causnet)](https://CRAN.R-project.org/package=causnet) [![CRAN downloads](http://cranlogs.r-pkg.org/badges/grand-total/causnet)](https://cran.r-project.org/package=causnet) [![status](https://tinyverse.netlify.com/badge/causnet)](https://CRAN.R-project.org/package=causnet)                                                                  |
| [**fdrci**](https://github.com/USCbiostats/fdrci)                         | Permutation-Based FDR Point and Confidence Interval Estimation [![CRAN status](https://www.r-pkg.org/badges/version/fdrci)](https://CRAN.R-project.org/package=fdrci) [![CRAN downloads](http://cranlogs.r-pkg.org/badges/grand-total/fdrci)](https://cran.r-project.org/package=fdrci) [![status](https://tinyverse.netlify.com/badge/fdrci)](https://CRAN.R-project.org/package=fdrci)                                                            |
| [**fmcmc**](https://github.com/USCbiostats/fmcmc)                         | A friendly MCMC framework [![CRAN status](https://www.r-pkg.org/badges/version/fmcmc)](https://CRAN.R-project.org/package=fmcmc) [![CRAN downloads](http://cranlogs.r-pkg.org/badges/grand-total/fmcmc)](https://cran.r-project.org/package=fmcmc) [![status](https://tinyverse.netlify.com/badge/fmcmc)](https://CRAN.R-project.org/package=fmcmc)                                                                                                 |
| [**GxEScanR**](https://github.com/USCbiostats/GxEScanR)                   | R version of GxEScan [![CRAN status](https://www.r-pkg.org/badges/version/GxEScanR)](https://CRAN.R-project.org/package=GxEScanR) [![CRAN downloads](http://cranlogs.r-pkg.org/badges/grand-total/GxEScanR)](https://cran.r-project.org/package=GxEScanR) [![status](https://tinyverse.netlify.com/badge/GxEScanR)](https://CRAN.R-project.org/package=GxEScanR)                                                                                    |
| [**HiLDA**](https://github.com/USCbiostats/HiLDA)                         | An R package for inferring the mutational exposures difference between groups[![](https://img.shields.io/badge/Bioconductor%20version-1.0.0-green.svg)](https://www.bioconductor.org/packages/HiLDA)[![](https://img.shields.io/badge/download-1384/total-blue.svg)](https://bioconductor.org/packages/stats/bioc/HiLDA)                                                                                                                            |
| [**hJAM**](https://github.com/USCbiostats/hJAM)                           | hJAM is a hierarchical model which unifies the framework of Mendelian Randomization and Transcriptome-wide association studies. [![CRAN status](https://www.r-pkg.org/badges/version/hJAM)](https://CRAN.R-project.org/package=hJAM) [![CRAN downloads](http://cranlogs.r-pkg.org/badges/grand-total/hJAM)](https://cran.r-project.org/package=hJAM) [![status](https://tinyverse.netlify.com/badge/hJAM)](https://CRAN.R-project.org/package=hJAM) |
| [**iMutSig**](https://github.com/USCbiostats/iMutSig)                     | A web application to identify the most similar mutational signature using shiny [![CRAN status](https://www.r-pkg.org/badges/version/iMutSig)](https://CRAN.R-project.org/package=iMutSig) [![CRAN downloads](http://cranlogs.r-pkg.org/badges/grand-total/iMutSig)](https://cran.r-project.org/package=iMutSig) [![status](https://tinyverse.netlify.com/badge/iMutSig)](https://CRAN.R-project.org/package=iMutSig)                               |
| [**jsPhyloSVG**](https://github.com/USCbiostats/jsPhyloSVG)               | htmlwidgets for the jsPhyloSVG JavaScript library [![CRAN status](https://www.r-pkg.org/badges/version/jsPhyloSVG)](https://CRAN.R-project.org/package=jsPhyloSVG) [![CRAN downloads](http://cranlogs.r-pkg.org/badges/grand-total/jsPhyloSVG)](https://cran.r-project.org/package=jsPhyloSVG) [![status](https://tinyverse.netlify.com/badge/jsPhyloSVG)](https://CRAN.R-project.org/package=jsPhyloSVG)                                           |
| [**LUCIDus**](https://github.com/USCbiostats/LUCIDus)                     | Latent and Unknown Cluster Analysis using Integrated Data [![CRAN status](https://www.r-pkg.org/badges/version/LUCIDus)](https://CRAN.R-project.org/package=LUCIDus) [![CRAN downloads](http://cranlogs.r-pkg.org/badges/grand-total/LUCIDus)](https://cran.r-project.org/package=LUCIDus) [![status](https://tinyverse.netlify.com/badge/LUCIDus)](https://CRAN.R-project.org/package=LUCIDus)                                                     |
| [**MergeBinaryDosage**](https://github.com/USCbiostats/MergeBinaryDosage) | R package for merging binary dosage files [![CRAN status](https://www.r-pkg.org/badges/version/MergeBinaryDosage)](https://CRAN.R-project.org/package=MergeBinaryDosage) [![CRAN downloads](http://cranlogs.r-pkg.org/badges/grand-total/MergeBinaryDosage)](https://cran.r-project.org/package=MergeBinaryDosage) [![status](https://tinyverse.netlify.com/badge/MergeBinaryDosage)](https://CRAN.R-project.org/package=MergeBinaryDosage)         |
| [**partition**](https://github.com/USCbiostats/partition)                 | A fast and flexible framework for agglomerative partitioning in R [![CRAN status](https://www.r-pkg.org/badges/version/partition)](https://CRAN.R-project.org/package=partition) [![CRAN downloads](http://cranlogs.r-pkg.org/badges/grand-total/partition)](https://cran.r-project.org/package=partition) [![status](https://tinyverse.netlify.com/badge/partition)](https://CRAN.R-project.org/package=partition)                                 |
| [**pfamscanr**](https://github.com/USCbiostats/pfamscanr)                 | An R client for EMBL-EBI’s PfamScan API [![CRAN status](https://www.r-pkg.org/badges/version/pfamscanr)](https://CRAN.R-project.org/package=pfamscanr) [![CRAN downloads](http://cranlogs.r-pkg.org/badges/grand-total/pfamscanr)](https://cran.r-project.org/package=pfamscanr) [![status](https://tinyverse.netlify.com/badge/pfamscanr)](https://CRAN.R-project.org/package=pfamscanr)                                                           |
| [**polygons**](https://github.com/USCbiostats/polygons)                   | Flexible functions for computing polygons coordinates in R [![CRAN status](https://www.r-pkg.org/badges/version/polygons)](https://CRAN.R-project.org/package=polygons) [![CRAN downloads](http://cranlogs.r-pkg.org/badges/grand-total/polygons)](https://cran.r-project.org/package=polygons) [![status](https://tinyverse.netlify.com/badge/polygons)](https://CRAN.R-project.org/package=polygons)                                              |
| [**rphyloxml**](https://github.com/USCbiostats/rphyloxml)                 | Read and write phyloXML files in R [![CRAN status](https://www.r-pkg.org/badges/version/rphyloxml)](https://CRAN.R-project.org/package=rphyloxml) [![CRAN downloads](http://cranlogs.r-pkg.org/badges/grand-total/rphyloxml)](https://cran.r-project.org/package=rphyloxml) [![status](https://tinyverse.netlify.com/badge/rphyloxml)](https://CRAN.R-project.org/package=rphyloxml)                                                                |
| [**selectKSigs**](https://github.com/USCbiostats/selectKSigs)             | Selection of K in finding the number of mutational signatures[![](https://img.shields.io/badge/Bioconductor%20version-1.0.0-green.svg)](https://www.bioconductor.org/packages/selectKSigs)[![](https://img.shields.io/badge/download-707/total-blue.svg)](https://bioconductor.org/packages/stats/bioc/selectKSigs)                                                                                                                                 |
| [**slurmR**](https://github.com/USCbiostats/slurmR)                       | slurmR: A Lightweight Wrapper for Slurm [![CRAN status](https://www.r-pkg.org/badges/version/slurmR)](https://CRAN.R-project.org/package=slurmR) [![CRAN downloads](http://cranlogs.r-pkg.org/badges/grand-total/slurmR)](https://cran.r-project.org/package=slurmR) [![status](https://tinyverse.netlify.com/badge/slurmR)](https://CRAN.R-project.org/package=slurmR)                                                                             |
| [**xrnet**](https://github.com/USCbiostats/xrnet)                         | R Package for Hierarchical Regularized Regression to Incorporate External Data [![CRAN status](https://www.r-pkg.org/badges/version/xrnet)](https://CRAN.R-project.org/package=xrnet) [![CRAN downloads](http://cranlogs.r-pkg.org/badges/grand-total/xrnet)](https://cran.r-project.org/package=xrnet) [![status](https://tinyverse.netlify.com/badge/xrnet)](https://CRAN.R-project.org/package=xrnet)                                            |
| [**xtune**](https://github.com/USCbiostats/xtune)                         | An R package for Lasso and Ridge Regression with differential penalization based on prior knowledge [![CRAN status](https://www.r-pkg.org/badges/version/xtune)](https://CRAN.R-project.org/package=xtune) [![CRAN downloads](http://cranlogs.r-pkg.org/badges/grand-total/xtune)](https://cran.r-project.org/package=xtune) [![status](https://tinyverse.netlify.com/badge/xtune)](https://CRAN.R-project.org/package=xtune)                       |
