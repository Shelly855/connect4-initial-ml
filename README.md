# Connect 4 – ML Agent Training

This repository trains a basic machine learning agent to predict outcomes in Connect 4 using the UCI dataset.

---

## Table of Contents

- [Connect 4 – ML Agent Training](#connect-4--ml-agent-training)
- [Overview](#overview)
- [Files](#files)
- [References](#references)
- [Optional Setup](#optional-setup)

---

## Overview
Trains a model to predict the final outcome of a Connect 4 board.
It differs from the models used in the [final game](https://github.com/Shelly855/connect4-ai), which predict the best move instead.

---

## Files

- `connect4_dataframe.ipynb` – Preprocesses the UCI dataset and trains an outcome-predicting model
- `connect-4.data` – UCI dataset of historical Connect 4 games  
- `ml_agent.pkl` – Model saved from this notebook

---

## References
- Connect 4 dataset from UCI Machine Learning Repository:
  - https://archive.ics.uci.edu/dataset/26/connect+4
- Scikit-learn: Machine Learning in Python
  - https://scikit-learn.org/stable/index.html
 
---

## Optional Setup

To rerun the notebook locally:

1. Ensure Python 3 is installed.
2. Install required packages:
  ```bash
  pip install pandas scikit-learn numpy
  ```
3. Open and run the notebook: `connect4_dataframe.ipynb`
> The notebook was created in Jupyter Notebook. You can also open it in VS Code with the Jupyter extension.
