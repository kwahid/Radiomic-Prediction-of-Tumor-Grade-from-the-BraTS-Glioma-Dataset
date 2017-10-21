# Radiomic-Prediction-of-Tumor-Grade-from-the-BraTS-Glioma-Dataset
Folder corresponding to 2017 summer/fall project at MD Anderson Cancer Center. Correspondance: kareem.a.wahid@uth.tmc.edu.

## This repo contains the following files: 
Folder containing input files neccessary for running notebook (grades_t1ce_label1.csv, grades_t1ce_label4.csv, grades_flair_label2.csv). <br><br>
Jupyter notebook of code implementation (Radiomic Glioma Prediction Jupyter Notebook.ipynb). <br><br>
HTML copy of Jupyter notebook (Radiomic Glioma Prediction Jupyter Notebook.html).<br><br>
Parameter file used in radiomic feature extaction (exampleMR_NoResampling.yaml). <br><br>
2 picture files used in the notebook (workflow_figure.png, workflow_overview.png). <br><br>

## Utilized the following python libraries in project: 
pyradiomics v.1.3.0 to generate features of dataset. http://pyradiomics.readthedocs.io/en/latest/ <br><br>
pandas for data manipulation.<br><br>
sklearn for machine learning.<br><br>
imblearn for SMOTE upsampling. <br><br>
matplotlib for graphing.<br><br>
seaborn for data visualizations. <br><br>
statsmodels for ANOVA statistical test. <br><br>
