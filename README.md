# THESIS-Automated-Short-Answer-System-using-SentenceBERT
Implementation of Automated Short Answer System using SentenceBERT

## Preprocessing text
1. Empty handling
2. lowercasing
3. normalize repeated character
4. remove URL, emails, number, symbols, and extra whitespace

## Done Trial
1. sBERT all-MiniLM-L6-v2 + Linear Regression 
2. sBERT all-MiniLM-L6-v2 + feature engineering + Linear Regression 
3. sBERT all-mpnet-base-v2 + feature engineering + Linear Regression
4. sBERT all-mpnet-base-v2 + feature engineering + LightGBM
5. sBERT all-mpnet-base-v2 + feature engineering + XGBoost

## Quick Report
1. Changing the sBERT into mpnet-base-v2 increases the Pearson and decreases the MAE (gud one)
2. Dospem suggested to use non-linear model for the scoring model
3. Dont erase numbers on preprocessing the dataset (might be the important feature)

ttp smgt, ttp wras, bisa bisa bisa
