﻿# ShayaSimpleSentimentTask

I'm going to write this document in the order that the code should run in:  
  
**1- Preprocess:**  
File: preprocess.py  
Input: Dataset/DeepSentiPers-original.csv  
Output: Dataset/Preprocessed_Data  
Description: Keeps only some punctuation and Farsi characters. Does text normalization (and stemming) usig Hazm. Adds space before punctuation.  
  
**2- Train test split:**  
File: train_test_split.py  
Input: Dataset/Preprocessed_Data  
Output: Dataset/Preprocessed_Train_Data.csv, Dataset/Preprocessed_Test_Data.csv  
