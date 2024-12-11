# Spectral-Clustering
This repository contains the notebooks used to create the plots for my Bachelor's thesis "Spectrales Clustering und Diffusionsabbildungen" (see BA Spectrales Clustering und Diffusionsabbildungen.pdf).

Spectral Clustering describes a clustering algorithm that uses kernels to transform data into a similarity graph and then uses k-means on the eigenvectors of specific laplace matrices of the resulting graph.
This has the advantage that highly non-convex clusters can also be identified. 

In my bachelor's thesis, I analyzed the underlying mathematics (in particular the optimization problem and the connection to diffusion mappings for random walks on a graphs). 
Furthermore, I applied the algorithm in python to small sample datasets to find rules of thumb for the underlying hyperparameters. 

