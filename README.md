## Citation

This repository contains supplementary material associated with the Master’s dissertation:
"Mapping Minds with Machines: Integrating Structural and Functional Brain Information into Explainable Graph-Informed Neurobiologically Plausible Models."

If you use this data, please cite accordingly.

## Supplementary Material Organization

The supplementary materials are organized according to the structure of the dissertation.

### Chapter 3
This folder includes all binarized structural connectivity matrices used in this chapter.

### Chapter 4
The Chapter 4 folder is divided into three subfolders:

- **Cohens_d**: includes Cohen’s d values for every pair of brain regions, for both mentalizing and random classes.
- **Regions_within_Networks**: contains the complete table of brain regions assigned to each network, organized in descending order of network SHAP values.
- **SHAP_analysis**: divided into motor and social paradigms, this folder includes the full SHAP value distributions across all regions (360 regions).

### Chapter 5
The Chapter 5 folder is also divided into three subfolders:

- **Connectivity_Matrix**: contains the connectivity matrix used in this chapter, including subcortical regions from the HCPex atlas and interhemispheric connections.
- **Regions_within_Networks**: replicates the analysis performed in Chapter 4, adapted to the extended HCPex matrix.
- **SHAP_analysis**: includes figures with SHAP values for all 426 regions, separated by motor and social paradigms.

### Region Atlases

The files `MMP1.0_regions.xlsx` and `HCPex_regions.xlsx` provide a summary of all brain regions, including:
- long names  
- short names  
- hemispheres  
- lobes
- cortex
- MNI coordinates  

These correspond to the cortical-only atlas (HCP MMP1.0) and the extended atlas (HCPex), respectively. 
