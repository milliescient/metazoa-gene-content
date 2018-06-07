This repository contains the datasets and [RevBayes](https://github.com/revbayes/revbayes) script needed to reproduce the results in Pett et al. 2018.

The script `genecontent.Rev` is currently configured to analyse the `Meta36-Homo` dataset using 2 independent MCMC chains by default. The script will need to be modified for each dataset to read the proper data file, as well as achieve good convergence. The convergence statistics reported in the manuscript were achieved using many more Metropolis-coupled chains. Please modify the run configuration to suit your computational requirements.

For best results, use [biphy](https://github.com/willpett/biphy).