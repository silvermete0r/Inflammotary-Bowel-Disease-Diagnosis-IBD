# Inflammotary-Bowel-Disease-Diagnosis-IBD

**Source: https://www.kaggle.com/competitions/genetic-based-diagnosis-of-patients/**

## Task
Your task is to create a binary classifier to distinguish between UC and CD patients by using the provided train dataset. After that, you need to predict a diagnosis(UC or CD) for patients from the test dataset.

## Introduction
An inflammatory bowel disease is a group of inflammatory conditions of the intestines. It is divided into Chron’s disease (CD) and ulcerative colitis (UC). Crohn's disease affects the small intestine and large intestine, as well as the mouth, esophagus, and stomach, whereas ulcerative colitis primarily affects the colon and the rectum. These two diseases are very similar in symptoms but have good treatment tactics and prognosis differences. Therefore, it turns out that differential diagnosis is critical. In the classical case, to distinguish the two diseases, a sufficiently traumatic procedure is used, which is a histological analysis of the biopsy from the damaged area. That in case of active disease can negatively affect the patient’s condition. Therefore, methods are being developed for more gentle diagnostics. The proposed project aims to develop a method for the differential diagnostics of IBD based on clinical and genetic data of patients using machine learning.

## Description of data
We created two datasets. The first dataset(Clinical_Data.train.txt and Genotype.train.txt) consisted of 1190 CD patient samples data and 800 UC patient samples data. The second dataset(Clinical_Data.test.txt and Genotype.test.txt) is a test dataset. It consists of 20 CD patients samples data and 20 UC patients samples data.
> For each patient in these datasets, we provide clinical and genotype data.
Clinical data(Clinical_Data.train.txt and Clinical_Data.test.txt) consists of weight, height, age of diagnosis, biochemical laboratory values, smoke status, and gender. Laboratory values can be saturated. Such values are marked by < and > signs.
Genotype data(Genotype.train.txt and Genotype.test.txt) consists of data for 378 biallelic SNP markers coded in three symbol alphabet codes (-1,1 homozygote and 0 - heterozygote )
> Clinical and genotype data may contain missing values. Each of the files with data is a tab-delimited table. The first column of these tables contains the patient ID. Each patient in the dataset corresponds to one line in the file. Diagnosis for patients from the training dataset can be found in column “Diag” of Clinical_Data.train.txt.

## Acknowledgment
This task was designed by Artem Kasianov with Quantori and published by GDSC Nazarbayev University
