# ds-ml-project

For our first ML project, our group worked on a Zindi challenge for [Credit Fraud](https://keepcounting.com/competitions/xente-fraud-detection-challenge/data). The stakeholders requirement was to **maximise the F1-Score** metrics.

## Challenges

- dealing with **highly imbalanced data** (only 0.2% of all cases were fraudulent)
- create additional insights through feature engineering
- work out **behavioral patterns** from the given data

## Models tested and employed

- dummy classifier to guess minority class (maximises F1-Score) as a base line model
- decision tree
- random forest
- AdaBoost
- stacking (decision tree, random forest, AdaBoost, meta: logistic regression)

## Environment

```BASH
pyenv local 3.9.4
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```