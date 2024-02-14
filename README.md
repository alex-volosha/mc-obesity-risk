# Multi-Class Prediction of Obesity Risk

The goal of this competition is to use various factors to predict obesity risk in individuals, which is related to cardiovascular disease.

## Data
The dataset for this competition (both train and test) was generated from a deep learning model trained on the Obesity or CVD risk dataset. Feature distributions are close to, but not exactly the same, as the original. 
train.csv - the training dataset; NObeyesdad is the categorical target
test.csv - the test dataset; your objective is to predict the class of NObeyesdad for each row

## Evaluation

For each id row in the test set, I predict the class value of the target, NObeyesdad

## Requirements and Environment

Requirements:
- pyenv with Python: 3.11.3

Environment: 

```Bash
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```