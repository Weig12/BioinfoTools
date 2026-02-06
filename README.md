# BioinfoTools
A list of bioinformatics tools

## Ducklake and Zymo Database
- https://ducklake.select/ Ducklake consists of a catalog database (DuckDB, SQLite, PostgreSQL, or MySQL) of parquet files an a storage of parquet files. 

## AI in bioinfo
- Conversational AI agent for precision oncology: AI-HOPE-WNT integrates clinical and genomic data to investigate WNT pathway dysregulation in colorectal cancer
  https://pubmed.ncbi.nlm.nih.gov/40860720/
- Identifying patients with undetected colorectal cancer: an independent validation of QCancer (Colorectal)  2012
  https://pmc.ncbi.nlm.nih.gov/articles/PMC3394989/  
- Development and validation of risk prediction algorithms to estimate future risk of common cancers in men and women: prospective cohort study  
  https://pubmed.ncbi.nlm.nih.gov/25783428/  
- Identifying patients with undetected gastro-oesophageal cancer in primary care: External validation of QCancer® (Gastro-Oesophageal) 2013  
  https://pubmed.ncbi.nlm.nih.gov/23159533/
- CRC risk in SEER https://docs.google.com/document/d/1OtJ5tO8VW9SNnDrOCyjm79MnlVB6rY-BKATKmHih77c/edit?tab=t.0  
- About the Colorectal Cancer Risk Assessment Calculator https://ccrisktool.cancer.gov/about.html
- Cox proportional hazards model https://docs.google.com/document/d/1T9zZauLaAzsncaUUuusJYAdyce6X8AjYbwxYwmu7uLs/edit?tab=t.0  
  https://docs.google.com/document/d/1lD9JAb80G5ZQ4O_oV3k2eHMFEf488VfkXLwhv1oaM6c/edit?tab=t.0
- **CRC 10-yr risk** https://qcancer.org/10yr/male/index.php  
- List of awesome code, papers, and resources for AI/deep learning/machine learning/neural networks applied to oncology.
  https://github.com/cbailes/awesome-ai-cancer/blob/master/README.md
- 

## DMR or read-level analysis
- DMRseq R package - https://www.bioconductor.org/packages/release/bioc/html/dmrseq.html  
vignettes at https://www.bioconductor.org/packages/release/bioc/vignettes/dmrseq/inst/doc/dmrseq.html
- **mHapBrowser**: a comprehensive database for visualization and analysis of DNA methylation haplotypes
  https://pmc.ncbi.nlm.nih.gov/articles/PMC10767976/ and https://mhap.sibcb.ac.cn/  
  https://github.com/yoyoong/mHapSuite and https://academic.oup.com/bioinformatics/article/37/24/4892/6305824?login=false  
  https://jiantaoshi.github.io/mHap/index.html  
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
- HumanMetagenomeDB: Genetic and Epigenetic Marker-Based DNA Test of Stool Is a Promising Approach for Colorectal Cancer Screening
  https://academic.oup.com/nar/article/49/D1/D743/5998395 and https://web.app.ufz.de/hmgdb/
- 

## Synthetic Data tools
- Synthetic Data Vault https://github.com/sdv-dev/SDV
- Milo-ML https://app.milo.ai/home/b889e113-df65-45e7-b563-8f2a919d1419  
- A novel and fully automated platform for synthetic tabular data generation and validation **STNG MILO**
  https://pubmed.ncbi.nlm.nih.gov/39375404/
- CRC data Kaggle https://www.kaggle.com/code/shuto210/eda-colorectal-cancer-risk/input  89945 samples, likely synthetic data  
  df = pd.read_csv("/kaggle/input/colorectal-cancer-risk-and-survival-data/colorectal_cancer_prediction.csv")
  https://www.researchgate.net/publication/391140390_Colorectal_Cancer_Prediction_Based_on_Random_Forest_Approach  
- CRC global data Kaggle https://www.kaggle.com/datasets/ankushpanday2/colorectal-cancer-global-dataset-and-predictions (likely synthetic data)  
  df = pd.read_csv("/kaggle/input/colorectal-cancer-global-dataset-and-predictions/colorectal_cancer_dataset.csv")  167,497 rows, 28 columns  
- Colorectal datasets https://cdas.cancer.gov/datasets/plco/22/
- https://www.cbioportal.org/datasets  
  Cercek 2020: https://www.cbioportal.org/study/summary?id=crc_eo_2020 1516 samples: Germline, somatic.  
  https://pmc.ncbi.nlm.nih.gov/articles/PMC8634406/   
- https://www.aacr.org/professionals/research/aacr-project-genie/bpc/crc-public-release/ BPC CRC v2.0-public, genomic and phenomic data  
  https://www.synapse.org/Synapse:syn27056172/wiki/616601 and https://www.aacr.org/wp-content/uploads/2023/01/2022_CRC-2.0-Public_graphics.pdf  
  https://www.aacr.org/wp-content/uploads/2022/11/GENIE-BPC-CRC-v2.0-public-Analytic-Data-Guide-v2.pdf
  https://docs.google.com/document/d/1XgazrppVspDye4lGDujeZs8GA70EifzuaNj4qMWQ3iY/edit?tab=t.0  
- https://docs.google.com/document/d/1E07QJFT-bwOTy5Vfv8H9sKe1saNET2KmAAGISVpFJuc/edit?tab=t.0
- CRC synthetic data 1000 samples and 15 columns: https://www.kaggle.com/code/fot66hg76/crc-risk-classifier/input  
  data df = pd.read_csv('/kaggle/input/colorectal-cancer-dietary-and-lifestyle-dataset/crc_dataset.csv')
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
- **Cologuard trial 2014**: Multitarget Stool DNA Testing for Colorectal-Cancer Screening
  https://www.nejm.org/doi/full/10.1056/NEJMoa1311194 and https://www.nejm.org/doi/suppl/10.1056/NEJMoa1311194/suppl_file/nejmoa1311194_appendix.pdf  
- Integrating Omics Data and AI for Cancer Diagnosis and Prognosis https://pmc.ncbi.nlm.nih.gov/articles/PMC11240413/
- PRISM (PRognostic marker Identification and Survival Modelling through Multi-omics Integration)
  https://pmc.ncbi.nlm.nih.gov/articles/PMC12540658/
- Cancer Research Data Commons https://datacommons.cancer.gov/explore/datasets
  Genetics and Epidemiology of Colorectal Cancer Consortium
- https://www.kaggle.com/datasets/erdemtaha/cancer-data/code Kaggle cancer data df = pd.read_csv("/kaggle/input/cancer-data/Cancer_Data.csv")  
- Genomic Data Commons https://www.cancergenomicscloud.org/datasets
- **The evolutionary progression of cancers** (Gene expression control by methylation and DNA-derived functional RNAs) Dr. Jia shared  
  https://www.academia.edu/2998-7741/1/2/10.20935/AcadOnco7415?email_action=download  
- Genetics, Cytogenetics, and Epigenetics of Colorectal Cancer https://pmc.ncbi.nlm.nih.gov/articles/PMC3070260/
- A systematic review and meta-analysis of **familial colorectal cancer risk** https://pubmed.ncbi.nlm.nih.gov/11693338/ Relative Risk 
- Clinical Application of Multigene Panels: Challenges of Next-Generation Counseling and Cancer Risk Management https://pubmed.ncbi.nlm.nih.gov/26484312/
- A **New Comprehensive Colorectal Cancer Risk Prediction Model** Incorporating Family History, Personal Characteristics, and Environmental Factors https://pubmed.ncbi.nlm.nih.gov/31932410/
- Risk Model for Colorectal Cancer in Spanish Population Using Environmental and Genetic Factors: Results from the MCC-Spain study https://pmc.ncbi.nlm.nih.gov/articles/PMC5324108/

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
- SEER CRC stats https://seer.cancer.gov/statfacts/html/colorect.html
- Beyond colonoscopy, faecal DNA mutation screening provides a potential and viable path to early colorectal cancer detection Yr2025  
  https://pmc.ncbi.nlm.nih.gov/articles/PMC12789060/  
-

## Modeling
- **SEERexplorer** for CRC incidence https://seer.cancer.gov/statistics-network/explorer/  
- **SEERStat software** for calculating cancer incidence, survival, etc https://seer.cancer.gov/seerstat/download/  
- Development and validation of risk prediction algorithms to estimate future risk of common cancers in men and women: prospective cohort study  
  https://bmjopen.bmj.com/content/5/3/e007825?cpetoc=&int_source=trendmd&int_medium=cpc&int_campaign=usage-042019  
- AutoML: https://docs.google.com/document/d/1CEodS17vExYBMsgueVGy6Z0RnR-IGJJdRg3ZWWtV3us/edit?tab=t.0  
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
- A new comprehensive colorectal cancer risk prediction model incorporating family history, personal characteristics, and environmental factors
  https://pmc.ncbi.nlm.nih.gov/articles/PMC7060114/
- Development and validation of risk prediction algorithms to estimate future risk of common cancers in men and women: prospective cohort study
  https://pmc.ncbi.nlm.nih.gov/articles/PMC4368998/
- Prevalence and Penetrance of Major Genes and Polygenes for Colorectal Cancer https://pmc.ncbi.nlm.nih.gov/articles/PMC5336409/
- **Logistic Regression Explained** https://medium.com/@msong507/logistic-regression-explained-2d1b8babe6c1
- 
  
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
- cfOmics: a cell-free multi-Omics database for diseases https://academic.oup.com/nar/article/52/D1/D607/7283892
- 

## EPIC array v2 clocks
- ENmix R package https://www.bioconductor.org/packages/release/bioc/vignettes/ENmix/inst/doc/ENmix.html  
- methylclock R package (18 public clocks) https://www.bioconductor.org/packages/release/bioc/vignettes/methylclock/inst/doc/methylclock.html  
- 
