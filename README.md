# CUPfinder

Predict tissue of origin of a tumor based on RNA expression data.

Carcinoma of unknown primary (CUP) is a metastatic cancer in which the tissue of origin (TOO) cannot be determined using conventional methods. CUP is often associated with a poor prognosis; however, therapies directed at the original cancer tissue can significantly improve patient outcomes. This highlights the importance of developing accurate computational approaches to infer the TOO. In this study, we employ CatBoost, a machine learning algorithm based on gradient boosting with decision trees, to predict the TOO. The model is trained and validated using RNA expression data from 4,500 patient samples representing 10 cancer types from the Cancer Genome Atlas (TCGA) and tested on a metastatic TCGA dataset containing 355 samples.

