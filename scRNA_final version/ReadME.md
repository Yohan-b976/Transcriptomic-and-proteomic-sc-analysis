# scRNA-seq Pipeline

This pipeline was built during a 4-month internship in the MVD team at IRIM, under the supervision of Willy Lutz.  
This can be considered as my first major project, and I am happy to present the result of my work.

## Goal of this pipeline

This pipeline is designed to process single-cell RNA-seq data using different programs and methods.  
It is composed of 5 Python files (Jupyter Notebooks) and 1 R file.

**Jupyter Notebook files (Python):**  
- Pipeline_QC v0.3  
- Prediction_Integration v0.3  
- Annotation_Mapping  
- SEACells_Meta v0.2  
- DEG v0.2  

**R file:**  
- QC_R (used for scDblFinder)

## Getting started:  
#### The data goes through the following process:  
- **Preprocessing**: Remove doublets, outliers and poor quality cells. This step is done using :  
  * Pipeline_QC v0.3  
  * QC_R (used for scDblFinder)  
- **Prediction and annotations**: Do predictions of the cell types and annotate the maps accordingly. This step is done using:  
  * Prediction_Integration v0.3  
  * Annotation_Mapping  
- **Metacell and differential expression**: Create metacells based on SEACells software and do the DEGs for each cell type. This step is done using:
  - SEACells_Meta v0.2
  - DEG v0.2  



---

This pipeline was developed using nasal mucosa data infected or not by HCoV-229E.  
With some modifications, it can be adapted to process any scRNA-seq dataset.

# Contact:
Email: yohanbeaumatin@gmail.com


