# Drug Repurposing for Hyperlipidemia Associated Disorders: An Integrative Network Biology and Machine Learning Approach
This repository contains the following files:
* CandidatesRandomForest.ipynb: The script is for rfc classifier training and prediction on data, it also has code for tasks such as generating ROC curves, cross validation and getting prediciton probabilities.
* Drug_M_Des_Downloads.ipynb: The script is to obtain MOL and SMILES data for DrugBank Ids
* Gene_Symbol_Conversion.ipynb: The script is a simple web scraping program for obtaining hsa ids, from a comma separated list of gene symbols/names.
* Data
  * DescriptorsFinal.csv: Contains dataset with 134 data points for rfc classifier training.
  * Descriptors_PredictionSet.csv: This contains the data of the candidates for which we required predictions.
  * CandidatePredictions_Proba.csv: The file has prediction probabilities for candidates given by the classifier.
  * sample_dbIds_geneSym: The folder has sample files for Drug_M_Des_Downloads.ipynb and Gene_Symbol_Conversion.ipynb scripts.
