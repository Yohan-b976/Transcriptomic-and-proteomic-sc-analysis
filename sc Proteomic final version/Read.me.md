# scRNA-seq Pipeline

This pipeline was built during a 4-month internship in the MVD team at IRIM, under the supervision of Willy Lutz.  
This can be considered as my first major project, and I am happy to present the result of my work.

## Goal of this pipeline

This pipeline is designed to process single-cell Proteomic data using different programs and methods.  
It is composed of 3 Python files (Jupyter Notebooks).

**Jupyter Notebook files (Python):**  
- scProteomic_data_preparation  
- Cell type assignation 0.4
- Mapping & Annotations 0.3
- test sur int et normalisation  


## Getting started:  
#### The data goes through the following process:  
- **Preprocessing**: Data formatting and correction of naming errors.
This step is done using :  
  * scProteomic_data_preparation   
- **Prediction and annotations**: Do predictions of the cell types and annotate the maps accordingly. 
This step is done using:  
  * Mapping & Annotations 0.3 
- **Test and tries**: Test of differents parameters and programms to look at the impact on the data. 
This step is done using:
  - Cell type assignation 0.4  
  - test sur int et normalisation  


---

This pipeline was developed using nasal mucosa data infected or not by HCoV-229E.  
With some modifications, it can be adapted to process any scRNA-seq dataset.

# Contact:
Email: yohanbeaumatin@gmail.com
