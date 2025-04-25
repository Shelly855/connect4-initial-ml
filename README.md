# Connect 4 – Initial ML Agent Training Attempt

This project folder contains an early experiment training a basic machine learning agent to predict outcomes in Connect 4 using the UCI dataset.

---

## Table of Contents

- [Connect 4 – Initial ML Agent Training Attempt](#connect-4--initial-ml-agent-training-attempt)
- [Overview](#overview)
- [Files](#files)
- [References](#references)
- [Optional Setup](#optional-setup)
- [GitHub Version (Optional)](#github-version-optional)

---

## Overview
This was an early attempt at training a model to predict the final outcome of a Connect 4 board.
It differs from the models used in the final game, which predict the best move instead.

---

## Files

- `connect4_dataframe.ipynb` – Preprocesses the UCI dataset and trains an outcome-predicting model
- `connect-4.data` – UCI dataset of historical Connect 4 games  
- `ml_agent.pkl` – Model saved from this notebook (not used in final project)

---

## References
- Connect 4 dataset from UCI Machine Learning Repository:
  - https://archive.ics.uci.edu/dataset/26/connect+4
- Scikit-learn: Machine Learning in Python
  - https://scikit-learn.org/stable/index.html
 
---

## Optional Setup

If you'd like to rerun the notebook locally:

1. Ensure Python 3 is installed.
2. Install required packages:
  ```bash
  pip install pandas scikit-learn numpy
  ```
3. Open and run the notebook: `connect4_dataframe.ipynb`
> The notebook was created in Jupyter Notebook. You can also open it in VS Code with the Jupyter extension.

---

## GitHub Version (Optional)

[View this folder on GitHub](https://github.com/Shelly855/connect4-initial-ml)  
> **Note:** This GitHub link is optional and not required for marking. The repository may be updated after submission.
