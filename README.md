# Neuefische Machine learning project: "Flight Delay"

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) 


## Neuefische data science bootcamp
---
[Neuefische GmbH](https://www.neuefische.de/) provides, amongst other bootcamps, a data science course. Integral part of the learning pipeline are three main projects. This project is focussing on applying acquired knowledge about different machine learning  (ML) algorithms.


## Aims of the Machine learning project
---
In small working groups, a given data set is processed and analyzed by applying exploratory data analysis and consequently performing a corresponding feature engineering. The topics are based on different business models and demand the acquisition of related business knowledge to pass a task that is related to a machine learning problem.

### Flight delay challenge
---
This challenge is based on a [Zindi](https://zindi.africa/competitions/ai-tunisia-hack-5-predictive-analytics-challenge-2)  data science competition. 

### Data source
The given data set for this particular project is consists of two parts: 1) the AI Tunisair flight data and 2) the Python Airport data set.

### Methods and Results
- exploratory data analysis of both data sets
    * data cleaning
    * feature engineering
    * data visualization
- applying machine learning algorithms (supervised and unsupervised classification and/or regression algorithms)
- answering to business question of the project in form of lay presentation of the results (presentation.pdf)



## Installation
__Requirements:__
- pyenv with Python: 3.9.4

__Environment Installation:__

Use the requirements file in this repo to create a new environment.

```BASH
make setup 

#or 

pyenv local 3.9.4
python -m venv .venv
pip install --upgrade pip
pip install -r requirements.txt
```

__Usage:__

In order to train the model and store test data in the data folder and the model in models run:

```bash
#activate env
source .venv/bin/activate
python train.py  
```

In order to test that predict works on a test set you created run:

```bash
python predict.py models/linear_regression_model.sav data/X_test.csv data/y_test.csv
```
## Contributors/Authors of this ML project
* Martin Lützner
* Patrick Schmitz
* Christian Klingler

