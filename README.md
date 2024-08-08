# Comparative Analysis of Pancreatic Ductal Adenocarcinoma (PDAC) Sequencing Data
In this project, we aim to compare the gene expression profile of four sets of pancreatic samples:
1. Normal pancreas
2. Resectable PDAC
3. Metastatic PDAC
4. Matched PDAC liver metastasis  
  
To perform this, we gathered publicly available scRNA-seq data from Zhang et al (https://doi.org/10.1038/s41467-023-40727-7) and Chen et al (https://doi.org/10.1186/s12967-023-04051-4). Having aligned the data to the GRCh38 human genome reference using Cell Ranger, the data was preprocessed and integrated using Seurat and Harmony packages.  
This is an ongoing project and the results are still under interpretation.  
The following figures represent a part of the analyses that have been performed so far:  
  
**Figure1- Cellular landscape of all the samples after filtration and cell type assignment:**  
<img src="/1- Cellular landscape after filtering.png" alt="Cellular landscape of all the samples after filtration and cell type assignment" class="center" width="900">
  
**Figure2- Cellular landscape of all the samples split by the group of samples:**  
<img src="/2- Cellular landscape of all cells split by sample origin.png" alt="Cellular landscape of all the samples split by the group of samples" class="center" width="1200">
  
**Figure3- Canonical markers used for cell type assignment:**  
<img src="/3- Dot Plot of canonical markers used for defining cell clusters.png" alt="Canonical markers used for cell type assignment" class="center" width="750">
  
**Figure4- Cell ratio of cell types per sample group:**  
<img src="/4- Cell ratio of each cell cluster in each disease type.png" alt="Cell ratio of cell types per sample group" class="center" width="350">
  
**Figure5- Number of cell types per sample group:**  
<img src="/5- cell ratio of each cell type in each disease type.png" alt="Number of cell types per sample group" class="center" width="800">
  
# Analysis of Epithelial Cells #
  
**Figure6- Cellular landscape of epithelial cells:**  
<img src="/6- Cellular landscape of epithelial cells.png" alt="Cellular landscape of epithelial cells" class="center" width="700">
  
**Figure7- Cellular landscape of epithelial cells split by sample group:**  
<img src="/7- Cellular landscape of epithelial cells split by sample origin.png" alt="Cellular landscape of epithelial cells split by sample group" class="center" width="900">
  
**Figure8- Cell ratio of epithelial cells per sample group:**  
<img src="/8- Cell ratio of epithelial cells in each sample origin.png" alt="Cell ratio of epithelial cells per sample group" class="center" width="350">
  
**Figure9- Cellular landscape of epithelial cells grouped by PDAC subtype:**  
<img src="/9- Cellular landscape of epithelial cells grouped by subtypes.png" alt="Cellular landscape of epithelial cells grouped by PDAC subtype" class="center" width="700">
  
**Figure10- Cell ratio of epithelial cells per PDAC subtype:**  
<img src="/10- Cell ratio of epithelial cells in each subtype.png" alt="Cell ratio of epithelial cells per PDAC subtype" class="center" width="350">
  
**Figure11- Kaplan-Meier survival analysis of CSC genes (CD24, CD44, PROM1, ALDH1A1, CD9, SLC1A5):**  
<img src="/11- Kaplan-Meier survival analysis of CSC genes.JPG" alt="Kaplan-Meier survival analysis of CSC genes" class="center" width="850">
