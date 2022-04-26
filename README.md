This repository contains experiments and derivations for the paper entitled

"Efficient Model Evidence Computation in Tree-structured Factor Graphs".

## Setting up
Before implementing the experiments, we need to initialize an environment in Julia. This can be done by the following steps:
* In a terminal, navigate to the location where you store the repository after cloning
* type `julia`
* type `using Pkg`, or `]`
* type `Pkg.activate(".")`, or `activate .` if we use `]` in the previous step.
If you clone the repository and keep its name, you should see `(SiPS2022-EfficientModeEvidenceComputation) pkg>` in the terminal when you press `]`.

Now you can instantiate the project by `Pkg.instantiate()`, or `instantiate` if you press `]`. This will install all necessary packages for the experiments.

## Experiments
The repository contains 3 experiments located in 3 seperate files `Coin_toss.ipynb`, `HMM.ipynb` and `LGSSM.ipynb`. The experiments can be implemented by executing every code block in the corresponding files.

## Supplementary document
We also include a supplement document `sips2022_scalefactor_supplement.pdf` which contains the derivation for all scale factor update rules in the paper. 
