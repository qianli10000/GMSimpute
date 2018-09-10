# GTSimpute

GTSimpute is an R package that implements the Two-Step Lasso (TS-Lasso) and compound minimum to recover the abundance of missing peaks in mass spectrum analysis. TS-Lasso is a label-free imputation method that handles various types of missing peaks simultaneously. This package provides the procedure to generate missing peaks (or data)  for simulation study, as well as a tool to estimate and visualize the proportion of missing at random.

# Functions
## GTS.Lasso 
Generalized Two-Step Lasso for missing peaks' abundance imputation

## TS.Lasso 
Two-Step Lasso for missing peaks' abundance imputation

## missing.sim 
A pipeline to generate different patterns and proportions of missing peaks for simulation study

## MAR.est
A tool to estimate and visualize the proportion of random missing peaks (i.e. caused by preprocessing) 

# Install GTSimpute

#Clone and download GTSimpute to a local folder 'path'; extract it to 'path/GTSimpute-master'.

require(devtools)

install('path/GTSimpute-master')
