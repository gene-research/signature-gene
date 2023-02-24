# A Composite Machine Learning Approach to Discover Biomarkers and their Genetic Relevance on Ovarian Cancer Chemoresistance 
This repository contains the code for the paper "A Composite Machine Learning Approach to Discover Biomarkers and their Genetic Relevance on Ovarian Cancer Chemoresistance Based on A Chinese Clinical Dataset".

## Abstract
The purpose of this study is to discover the signature genes associated with ovarian cancer (OCa) chemoresistance (CR) using a composite machine learning approach.
A novel dynamic feature elimination random forest (DFE-RF) algorithm is presented in the first step of our suggested methodology to choose feature genes in accordance with the distribution of feature importance. The signature genes are identified in the second stage using a cox survival regression method based on progression-free survival (PFS). Using the proposed approach, seven signature genes were found in the ovarian cancer dataset from Peking University Third Hospital. Data processing metrices and a review of the biological literature are used to validate the discovered signature genes. SVM classifier is used to validate the performance of a model based on these signature genes, and experiments reveal that the accuracy, precision, recall, and area under the curve (AUC) in the test set are each 0.9602, 0.9875, 0.9571, and 0.9619, respectively. We find that all of the signature genes discovered in our study have been identified as biomarkers when we compare our results to the prior literature. The proposed composite machine learning method can also be used to identify the signature genes from the dataset of other diseases.

## Code
Signature gene selection and evaluation.ipynb contains the selection process of seven signature genes.

## Data
The raw sequencing data files of our cohort were deposited in the Chinese National Genomics Data Center (OMIX001152 and OMIX002249), https://ngdc.cncb.ac.cn/omix.
