# BioinfoTools
A list of bioinformatics tools

## DMR or read-level analysis
- DMRseq R package - https://www.bioconductor.org/packages/release/bioc/html/dmrseq.html  
vignettes at https://www.bioconductor.org/packages/release/bioc/vignettes/dmrseq/inst/doc/dmrseq.html
- mHapBrowser: a comprehensive database for visualization and analysis of DNA methylation haplotypes
  https://pmc.ncbi.nlm.nih.gov/articles/PMC10767976/
- MethylBERT enables read-level DNA methylation pattern identification and tumour deconvolution using a Transformer-based model
  https://pmc.ncbi.nlm.nih.gov/articles/PMC11742067/ PMID: 39824848
-

## Microbiome
- HUMAnN - HUMAnN is the next generation of HUMAnN (HMP Unified Metabolic Analysis Network). Pathway analysis.
  https://github.com/biobakery/humann
- Sourmash, Lefse, Maaslin,
- Meta-Analysis and Validation of a Colorectal Cancer Risk Prediction Model Using Deep Sequenced Fecal Metagenomes
  https://pmc.ncbi.nlm.nih.gov/articles/PMC9454621/ Yr2022, 32 species  
- QIITA - https://github.com/qiita-spots/qiita and QIIME 2.  
- 

## Synthetic Data tools
- Synthetic Data Vault https://github.com/sdv-dev/SDV
- A novel and fully automated platform for synthetic tabular data generation and validation **STNG MILO**
  https://pubmed.ncbi.nlm.nih.gov/39375404/
- CRC data Kaggle https://www.kaggle.com/code/shuto210/eda-colorectal-cancer-risk/input
  df = pd.read_csv("/kaggle/input/colorectal-cancer-risk-and-survival-data/colorectal_cancer_prediction.csv")  
- CRC global data Kaggle https://www.kaggle.com/datasets/ankushpanday2/colorectal-cancer-global-dataset-and-predictions

- 


## Cancer experts
- Stephen B. Baylin, MD, Johns Hopkins and Van Andel Institute   
  Epigenetic Determinants of Cancer https://pmc.ncbi.nlm.nih.gov/articles/PMC5008069/ PMID: 27194046  
  A decade of exploring the cancer epigenome — biological and translational implications
  https://pmc.ncbi.nlm.nih.gov/articles/PMC3307543/ PMID: 21941284  
  https://profiles.hopkinsmedicine.org/provider/stephen-b-baylin/2777062

- Susan Bullman  
  Microbiome in CRC  
  A distinct Fusobacterium nucleatum clade dominates the colorectal cancer niche  
  https://pmc.ncbi.nlm.nih.gov/articles/PMC11006615/ PMID: 38509359  

## Cancer papers
- Sex and smoking bias in the selection of somatic mutations in human bladder
  https://www.nature.com/articles/s41586-025-09521-x
- Cologuard trial 2014: Multitarget Stool DNA Testing for Colorectal-Cancer Screening
  https://www.nejm.org/doi/full/10.1056/NEJMoa1311194
- Integrating Omics Data and AI for Cancer Diagnosis and Prognosis https://pmc.ncbi.nlm.nih.gov/articles/PMC11240413/
- PRISM (PRognostic marker Identification and Survival Modelling through Multi-omics Integration)
  https://pmc.ncbi.nlm.nih.gov/articles/PMC12540658/
- Cancer Research Data Commons https://datacommons.cancer.gov/explore/datasets
  Genetics and Epidemiology of Colorectal Cancer Consortium
- https://www.kaggle.com/datasets/erdemtaha/cancer-data/code Kaggle cancer data df = pd.read_csv("/kaggle/input/cancer-data/Cancer_Data.csv")  
- Genomic Data Commons https://www.cancergenomicscloud.org/datasets
- 

## CRC samples
- DNA Methylation Profiling at Base-Pair Resolution Reveals Unique Epigenetic Features of Early-Onset Colorectal Cancer in Underrepresented Populations  
  https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE284325 Raw seq data + beta values
- Biological Age Acceleration and Colonic Polyps in Persons Under Age 50 (array) https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE282666
- Methylome, hydroxymethylome, and integrative transcriptome profiling in human CRC tissue and paired normal tissues  
  https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE87096 meDIP-seq RNA-seq
- Simultaneous methylation-level assessment of hundreds of CpG sites by targeted bisulfite PCR sequencing (TBPseq)
  https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE98921 46 cancer cell lines including CRC cell lines
- Active BRAF-V600E is the key player in generation of a sessile serrated polyp-specific DNA methylation profile (WGBS data set)  
  https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE110537 3 samples  
- Active BRAF-V600E is the key player in generation of a sessile serrated polyp-specific DNA methylation profile (Exome-seq data set)
  https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE110535 12 samples  
- DNA methylation analysisof KRAS mutated colorectal tumors and adjacent tissues from cancer patinets and KRAS mutated Aberrant Crypt Foci and matching normal crypts from healthy individuals by using RRBS  
  https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE95654  40 samples
- Comparative genome-wide DNA methylation analysis of colorectal tumor and matched normal tissues
  https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE39068 MethylCap-seq yr2012
- Identification of candidate predisposing copy number variants in familial and early-onset colorectal cancer patients
  https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE13429 SNP arrays  
- 

## Modeling
- MTLR: Multi-Task Logistic Regression models  
  https://square.github.io/pysurvival/models/mtlr_theory.html
- MTLR with survival modeling
  https://docs.google.com/document/d/108S3puGpEx3crJMNvQy9o7I-p2_e80OGVHFOu19Q2Zo/edit?tab=t.0
- Individual Survival Distributions Generated by Multi-Task Logistic Regression Yield a New Perspective on Molecular and Clinical Prognostic Factors in Gastric Adenocarcinoma
  https://pmc.ncbi.nlm.nih.gov/articles/PMC10887062/
- Deep Learning Based Multiomics Model for Risk Stratification of Postoperative Distant Metastasis in Colorectal Cancer
  https://pubmed.ncbi.nlm.nih.gov/40912950/
- Late fusion: Machine-Learning-Based **Late Fusion** on Multi-Omics and Multi-Scale Data for Non-Small-Cell Lung Cancer Diagnosis
  https://pmc.ncbi.nlm.nih.gov/articles/PMC9025878/ & https://github.com/pacocp/multiomic-fusion-NSCLC
- **Synthetic data production** for biomedical research https://pmc.ncbi.nlm.nih.gov/articles/PMC12066231/
- Synthetic data generation methods in healthcare: A review on open-source tools and methods
  https://pmc.ncbi.nlm.nih.gov/articles/PMC11301073/
- Precious2GPT: the combination of multiomics pretrained transformer and conditional diffusion for artificial multi-omics multi-species multi-tissue sample generation
  https://pmc.ncbi.nlm.nih.gov/articles/PMC11310469/
- Synthetic data generation methods in healthcare: A review on open-source **tools and methods**
  https://pmc.ncbi.nlm.nih.gov/articles/PMC11301073/ 2024 https://github.com/waldemar93/synthetic_data_pipeline/tree/main  
- Mimicking clinical trials with **synthetic acute myeloid leukemia patients** using generative artificial intelligence
  https://pubmed.ncbi.nlm.nih.gov/38509224/ 2024 https://github.com/waldemar93/synthetic_data_pipeline/tree/main
  Synthetic multimodal data at https://zenodo.org/records/8334265 .  1606 x 2 synthetic patients data
- **Synthcity**: facilitating innovative use cases of synthetic data in different data modalities  
  https://arxiv.org/pdf/2301.07573 and https://github.com/vanderschaarlab/synthcity  
- Can **synthetic data** be a proxy for real clinical trial data? A validation study?  **CRC synthetic data on only clinical, metadata**  
  https://pmc.ncbi.nlm.nih.gov/articles/PMC8055130/ Yr2021. Source data at https://data.projectdatasphere.org/  
  Suppl. at https://pmc.ncbi.nlm.nih.gov/articles/instance/8055130/bin/bmjopen-2020-043497supp001.pdf
- Synthetic Data Improve Survival Status Prediction Models in Early-Onset Colorectal Cancer https://pmc.ncbi.nlm.nih.gov/articles/PMC10830088/
  A synthetic population of 5,005 was generated from a data set of 1,253 patients with 93 clinical features.   
- Advancing breast cancer prediction: Comparative analysis of **ML models** and deep learning-based multi-model ensembles on original and synthetic datasets
  https://journals.plos.org/plosone/article?id=10.1371%2Fjournal.pone.0326221 Yr2025
  
## AI-assisted coding
- Building applications with GitHub Copilot agent mode https://learn.microsoft.com/en-us/training/modules/github-copilot-agent-mode/   
https://docs.google.com/document/d/1NxHgmBuGUO5FfvqIVrAyguDPGl_NNS4XNpEEcNMK4JE/edit?tab=t.0    
- ANZ | GitHub Copilot: The agent awakens: Building Applications with GitHub Copilot Agent Mode  
  https://www.youtube.com/watch?v=bFNgVwlFyxk
- Building applications with GitHub Copilot agent mode https://www.youtube.com/watch?v=XnC6cF1v5OY
- 

## Databases
- Efficient and accurate search in petabase-scale sequence repositories
  https://www.nature.com/articles/s41586-025-09603-w
- MetaGraph https://metagraph.ethz.ch/  
- MSK-CHORD https://github.com/clinical-data-mining https://pmc.ncbi.nlm.nih.gov/articles/PMC11655358/  
- MLOmics: Cancer Multi-Omics Database for Machine Learning https://www.nature.com/articles/s41597-025-05235-x
- Identification of cancer risk groups through multi-omics integration using autoencoder and tensor analysis
  https://www.nature.com/articles/s41598-024-59670-8?fromPaywallRec=false
- Integrative analysis of multi-omics data for liquid biopsy https://www.nature.com/articles/s41416-022-02048-2?fromPaywallRec=false
- 
