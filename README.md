# Mushroom Dataset Poisonous Prediction

### Link to notebook: [regression_neely.ipynb](https://github.com/bncodes19/ml-regression-neely/blob/main/regression_neely.ipynb)

## Overview
In this lab, the Medical Cost Personal dataset from Kaggle is analyzed.

Two types of models are employed for predicting the poisonous of a mushroom:
- Linear Regression: designed to predict a target variable based on the relationship between one or more features
- Pipeline Implementation: designed to preprocess multiple steps before training the model


## Sections of the analysis:
- Section 1: Import the Dataset
- Section 2: Data Exploration and Preparation
   - 2.1: Explore Data Patterns and Distributions
   - 2.2: Feature Engineering
- Section 3: Feature Selection and Justification
   - 3.1: Choose Features and Target
- Section 4: Train a Model (Random Forest)
   - 4.1 Split the data
   - 4.2 Train trhe model
   - 4.3 Evaluate performance
- Section 5: Compare Alternative Model
   - 5.1 Support Vector Machine
- Section 6: Final Thoughts and Insights

## Dataset 
Medical Cost Personal Dataset
- We use the Kaggle Dataset:
<https://www.kaggle.com/datasets/mirichoi0218/insurance>

## Python Library for Machine Learning: scikit-learn
We use scikit-learn, built on NumPy, SciPy, and matplotlib
   - Read more at <https://scikit-learn.org/>
   - Scikit-learn supports classification, regression, and clustering.
   - This project applies regression.

**Important:** Use a 2-step installation to avoid timeouts and partial installs:  
1. **First Install:** Install from `requirements.txt` with `scikit-learn` commented out.  
2. **Second Install:** Uncomment `scikit-learn` and rerun the install command.

---

## How to clone this project for further development:
Clone this repository:  
```shell
git clone https://github.com/bncodes19/ml-regression-neely
```
### To set up the virtual environment in the terminal:
``` shell
python3 -m venv .venv
```
4. Activate the virtual enivronment
``` shell
source .venv/bin/activate
```