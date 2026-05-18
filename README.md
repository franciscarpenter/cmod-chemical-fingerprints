# cmod-chemical-fingerprints
Repository containing code for analysis of condensate modulator (c-mod) chemical properties, as described in the manuscript "Chemical 'fingerprints' of condensate modulating drugs".

# Licenses
Code and notebooks are licensed under the Apache License 2.0.

Data files in `data/` are licensed under CC BY 4.0. Please provide attribution for any uses of the data provided.

# Contents
5 notebooks covering all of the analysis described are available in `notebooks/`:
1. `dpaint-cmod-vs-non-cmod.ipynb` includes the unvariate statistical and ML analyses comparing c-mods and non-c-mods identified from the d.paint screen
2. `cdcode-cmod-vs-non-c-mod.ipynb` inclues the same univariate statistical and ML analyses, but instead comparing CD-Code c-mods to d.paint non-c-mods
3. `correlation_num_condensates.ipynb` includes, for d.paint c-mods, analyses correlating the number of condensates modulated with chemical descriptor properties
4. `kinase_analysis.ipynb` includes, for d.paint c-mods and non-c-mods, analyses regarding the proportion of compounds that are annotated as kinase inhibitors
5. `cluster_by_structure_and_condensate.ipynb` includes, for d.paint c-mods that modulate only a single condensate, analysis into structural c-mod clusters and which condensates these clusters modulate

# How to run the notebooks
Input data required are available in `data/`, in a set of .csv and .xslx files.

The python packages required to run the notebooks are described in requirements.txt
