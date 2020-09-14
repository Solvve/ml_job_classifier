# Game score extraction

[![License](http://img.shields.io/badge/license-MIT-green.svg?style=flat)](https://github.com/Solvve/job_classifier/blob/master/LICENSE.txt)
[![Python 3.7](https://img.shields.io/badge/python-3.7-blue.svg)](https://www.python.org/downloads/release/python-378/)
[![SpaCy 2.3.0](https://img.shields.io/badge/spacy-2.3.0-blue)](https://spacy.io/)
[![scikit-learn 0.23.2](https://img.shields.io/badge/scikit_learn-0.23.2-blue)](https://scikit-learn.org/stable/)
[![Solvve](https://img.shields.io/badge/made%20in-solvve-blue)](https://solvve.com/)

## Description

This is an example of text classification on job description dataset.

For solving this problem we follow the next steps:
* Exploratory data analysis
* Data preprocessing
* Modeling
* Show job position based on description

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
