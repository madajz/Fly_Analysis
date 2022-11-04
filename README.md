# Fly_Analysis

This repo contains a beta version of the code to automatically analyze Drosophila experiemntal data. The code will read all data from a directory and attempt to run everything through appropriate analyses based on type of experiemnt (TG, Immune, Activity, RING, Longevity, and Fecundity). The success of this workflow running depends heavily on data being formatted correctly and identically across all files. Output consists of: a table of second generation p-values, heatmaps, and some exploratory plots. Full analysis methods and rationale are in the .rmd file. Code chunks can be removed as needed to only the experiments that were run. Figure dimensions will need to be manullay fixed to get good aspect ratios; I'm working on modifying figure dimensions as a function of the number of toxins. As stated this is a beta version, some testing is still being done to ensure accuracy of results.

Social Distancing will be added to this master rmd file.
