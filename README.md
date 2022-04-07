# News Classification With Deep Learning

## Introduction

This repository contains the source code for the implementation and training of our models, for the task of classifying news into 4 labels: **Satire, Hoax, Propaganda and Reliable news**

Due to the size limitations of the trained models and pre-processed datsets, the trained models and pre-processed are not available in this repository.

Training dataset was adapted from [here](https://github.com/BUPT-GAMMA/CompareNet_FakeNewsDetection/releases/tag/dataset).

---

## Repository Structure

```
/
|__ Analysis.ipynb (Main Dataset Analysis)
|__ DatasetAnalysis.ipynb (Further Dataset Analysis, plotting of graphs for report)
|__ PreprocessDataset.ipynb (Pre-processing of dataset and saving to csv files)
|__ ResumeTraining.ipynb (Script to continue training saved models)
|__ CNN_Model.ipynb (Implementation and Training of CNN model)
|__ LSTM_Model.ipynb (Implementation and Training of LSTM model)
|__ LSTM_Evaluation.ipynb (Evaluate LSTM model on balancedTest file)
|__ Evaluate_Sentence.ipynb (Evaluate individual/custom sentences on LSTM model)
|__ ML_Models.ipynb (Implementation and Training of NB, LR and MLP models)
|__ Random Forest.ipynb (Implementation and Training of Random Forest Model)
|__ BERT_Transformer.ipynb (Redacted BERT Model)
|__ BERT_Evaluaation.ipynb (File for evaluation of BERT Model - REDACTED)
```

---

## Quick Start

All files are in the form of Python Notebooks, and can be run without additional installation of external dependencies. Code dependencies are listed at the start of all files.

---

## Models

The repository contains the source code for training, and evaluation for the following models:

1. CNN
1. LSTM
1. Naive Bayes
1. Logistic Regression (No Tf-Idf)
1. Multi Layer Perceptron (No Tf-idf)
1. BERT (Redacted)

---

## Training Datasets

Our models utilise pre-processed versions of the original datasets to improve performance by reducing redundant data in the text.

Due to the size of the CSV files, they are not uploaded to the repository. The processed datasets can be created using the `PreprocessDataset.ipynb` file, and selecting the type of preprocessing to be done on the dataset.

This will output a CSV file which can be used in the model training files, and evaluation files.

---
