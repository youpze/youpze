# Hi, I'm Youp Zegers

I'm a bioinformatician based in Amsterdam and recently graduated cum laude from the MSc in Bioinformatics and Systems Biology (VU Amsterdam and University of Amsterdam, bioinformatics track). I build pipelines and machine learning models for genomics data. I'm looking for bioinformatics, data science and PhD positions.

## Research and pipeline work

### [wf-PHAVA](https://github.com/lumc-sasc/wf-PHAVA)
*LUMC, Sequencing Analysis Support Core. 10 month graduation internship, BSc Bioinformatics (Leiden University of Applied Sciences)*

PHAVA (PacBio HiFi Amplicon Variant calling Analysis) is a Nextflow pipeline that calls variants in "dark" regions of the genome, which are hard to resolve with short reads, using PacBio HiFi amplicon data. It runs quality control (FastQC, MultiQC), primer trimming with linked adapters (Cutadapt), alignment (minimap2), variant calling (DeepVariant) and phasing (WhatsHap). Tools are added as nf-core modules with Docker containers, and the pipeline runs on an HPC cluster using Singularity.

### Nigiri
*Amsterdam UMC, deparment of clinical genetics & bioinformatics department. 6 month master's internship*

Snakemake pipeline that detects imprinting disorders from DNA methylation data by comparing each patient against a control cohort. Reached 93.4% concordance with MS-MLPA, the current clinical standard, and is now being implemented in patient care, which is why the code is closed source. During this internship I also did the statistical analyses for a paper on uniparental disomy (see publications), and a second paper on multi-locus imprinting disturbances is in preparation.


### Non-coding driver mutations in breast cancer
*Netherlands Cancer Institute, Elzo de Wit lab. 6 month master's internship *

Trained 12 ChromBPNet models on TCGA breast cancer ATAC-seq data, one per tumor across four subtypes, and used them to score somatic variants in regulatory elements in silico to find candidate non-coding driver mutations. Analyses in Bash, Python and R on an HPC cluster, with the deep learning models trained on a GPU cluster. The code is not publicly available as it is intellectual property of the Netherlands Cancer Institute.


## Course projects

Overview of the group projects published on Github from my master's.

### [FOB_project](https://github.com/youpze/FOB_project)
*Fundamentals of Bioinformatics*

Benchmarking the missense variant impact predictors SIFT and PolyPhen-2 against ClinVar as a gold standard, with performance compared in ROC analysis.

### [CAT](https://github.com/youpze/CAT), Classification Assessment of Tumor Subtypes
*Bioinformatics for Translational Medicine*

Predicting breast cancer subtype (HER2+, HR+ or triple negative) from array CGH copy number profiles. Random forest combined with three feature selection strategies (random forest importance, PCA and correlation filtering), with all settings tuned in a repeated nested cross-validation to get an honest accuracy estimate on a small dataset.

### [Data-Mining](https://github.com/youpze/Data-Mining)
*Data Mining Techniques*

- **Mood prediction** from smartphone and experience sampling data. Cleaning, imputation, time window aggregation and feature engineering, followed by classical models and an LSTM.
- **Hotel search ranking** on Expedia data as a Kaggle competition. LightGBM LambdaRank, CatBoost tuned with Optuna and a ListNet neural network in PyTorch, blended into an ensemble optimised for NDCG@5. Our team placed 21st out of 148.

### [ScML](https://github.com/youpze/ScML), Scientific Machine Learning
*Scientific Machine Learning*

Predicting protein-protein interaction interface residues at residue and protein level. Compared logistic regression, random forest, SVM, XGBoost and our own neural networks, handled the strong class imbalance with under- and oversampling, and used SHAP and permutation importance to interpret the models.

<!--
## Currently building

A web app for journal clubs. Upload a paper, choose a format (for example one presenter per figure) and the presentation is split up for you. A side project to grow as a software engineer, private for now.
-->

## Skills
Languages | Python, R, Bash/Linux, SQL (SQLite, PostgreSQL), Java 
Workflows | Snakemake, Nextflow (nf-core), Conda, HPC, Docker, Singularity 
Machine learning | scikit-learn, PyTorch, TensorFlow, Keras, ChromBPNet 
Genomics | WGS, PacBio HiFi data, variant calling, DNA methylation, ATAC-seq, RNA-seq (DESeq2) 

## Contact

[LinkedIn](https://www.linkedin.com/in/youp-zegers-559187221/) or youpzegers2000@gmail.com
