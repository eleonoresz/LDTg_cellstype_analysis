# LDTg_cellstype_analysis

Analysis of the cells type in the LDTg using Allen scRNA repository (Cache)

# Goals
1) Understanding if cells type are more defined in cortical and midbrain areas compare to the pons
2) Comparing the LDTg distribution of cells type compared to other regions of the pons

# Methods
1) Vizualisation using UMAP
2) Classification accuracy using logistic regression
3) Analysis of the classifier error

# Results
1) Midbrain and pons area cells are slightly less separated by cells type but it could be due to the higher number of cell type in those areas
2) Compared to other areas of the pons, LDTg cells' type are not less separated
3) Most of the misclassification (overlapping cells' type) come from the confusion between cells expressing GABA and GABA-Glyc
