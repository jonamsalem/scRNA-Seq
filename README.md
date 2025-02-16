## scRNA-Seq Data Analysis

Centralize commonly used scRNA scripts with elaborate comments for novel users.

NOTE: each sub-directory has an in-depth README file to explain its purpose.

### Directories

`Preoprocessing` - Retrieve h5 file that contains feature expression data, convert to seurat, perform normalizatiom, filtering, sclaing, PCA, clustering, and UMAP. Visualize umap by genes to see differential expression by clusters.


`Integration` - Check and Corrects batch effects by identifying shared features across patients, aligning datasets using canonical correlation analysis (CCA), and generating an integrated Seurat object for unbiased clustering and visualization.
