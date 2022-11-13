## Data Description

The data for this analysis is sourced from [OncoDB](https://oncodb.org/), a comprehensive, open-source database containing cancer-associated gene expression profiles. Curated data is downloaded from 'Expression Data', which includes expression metrics across 37 distinct subtypes of cancer. Each .txt file within the .zip file contains a list of genes with the highest levels of differential expression between normal and cancer samples.

**Source:** https://oncodb.org/data_download.html  
**Paper:** https://doi.org/10.1093/nar/gkab970

### File Nomenclature

Files are named as \<cancer-abbreviation>.txt, i.e. BLCA.txt.

### Variables

The variables included in each file of the original dataset are listed below, along with their respective descriptions: 

|    Name                           |                          Description                                              | 
|-----------------------------------|-----------------------------------------------------------------------------------|
| Cancer type | TCGA Cancer Type |
| NCBI gene id | NCBI Gene ID |
| FDR adjusted p-value | adjusted student's t-test p-value |
| Cancer sample med | median expression level across cancer samples |
| Normal sample med | median expression levels across normal samples |
| log2 fold change | log2 transformed fold change, to quantify degree of upregulation/downregulation |
| p-value | student's t-test p-value |
| Gene symbol | gene symbol |
