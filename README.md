# Game score extraction

[![License](http://img.shields.io/badge/license-MIT-green.svg?style=flat)](https://github.com/Solvve/ml_job_classifier/blob/master/LICENSE.txt)
[![Python 3.7](https://img.shields.io/badge/python-3.7-blue.svg)](https://www.python.org/downloads/release/python-378/)
[![SpaCy 2.3.0](https://img.shields.io/badge/spacy-2.3.0-blue)](https://spacy.io/)
[![scikit-learn 0.23.2](https://img.shields.io/badge/scikit_learn-0.23.2-blue)](https://scikit-learn.org/stable/)
[![Solvve](https://img.shields.io/badge/made%20in-solvve-blue)](https://solvve.com/)

## Description

This is an example of text classification on job description dataset, using different classifiers with tuning techniques.

For solving this problem we follow the next steps:
* Exploratory data analysis
* Data preprocessing
* Modeling
* Show job position based on description

The classifier is built on [dataset](https://www.kaggle.com/bman93/dataset), which contains > 70k job descriptions belong to 30 job positions.

Example contains training 4 different classifiers with comparing results on validation dataset:

| Classifier | Accuracy |
|---|---|
| Naive Bayes classifier | 0.87 |
| LogisticRegression | 0.94 |
| DecisionTreeClassifier | 0.93 |
| LinearSVC classifier | 0.95 |


**Example**  
*Input text (job description)*:    

Our client is a leading innovator in manufacturing thousands of products that affect the lives of millions of people every day; and a strategic player in the Home Health, Personal Care, Electronics, Industrial and Transportation Markets. Specifics:
- Prepare support for and record required journal entries related to general ledger accounts
- Prepare monthly account reconciliations
- Support and actively participate in department initiatives
- Assist with Ad-hoc analysis and projects  

*Output (job position)*:  

Staff Accountant



## Installation

With Kaggle API download [dataset](https://www.kaggle.com/bman93/dataset):
```bash
kaggle datasets download -d bman93/dataset
```

Dependencies:
```bash
pip install -r requirements.txt
```

Optional:
```bash
python -m spacy download en_core_web_sm
```
