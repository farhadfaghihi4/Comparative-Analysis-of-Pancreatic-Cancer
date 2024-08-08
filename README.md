# Comparative Analysis of Pancreatic Ductal Adenocarcinoma (PDAC) Sequencing Data
In this project, we aim to compare the gene expression profile of four sets of pancreatic samples:
1. Normal pancreas
2. Resectable PDAC
3. Metastatic PDAC
4. Matched PDAC liver metastasis  
  
To perform this, we gathered publicly available scRNA-seq data from Zhang et al (https://doi.org/10.1038/s41467-023-40727-7) and Chen et al (https://doi.org/10.1186/s12967-023-04051-4). Having aligned the data to the GRCh38 human genome reference using Cell Ranger, the data was preprocessed and integrated using Seurat and Harmony packages.  
This is an ongoing project and the results are still under interpretation.  
The following figures represent a part of the analyses that have been performed so far:  
<img src="/1- Cellular landscape after filtering.png" alt="Cellular landscape of all the samples after filtration and cell type assignment" class="center" width="1200">
