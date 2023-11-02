# Fraud Detection in Electricity and Gas Consumption


We contributed in the Machine Learning Challenge on [Zindi.africa](https://zindi.africa/competitions/fraud-detection-in-electricity-and-gas-consumption-challenge).

The Tunisian Company of Electricity and Gas (STEG) is a public and a non-administrative company, it is responsible for delivering electricity and gas across Tunisia. The company suffered tremendous losses in the order of 200 million Tunisian Dinars due to fraudulent manipulations of meters by consumers.

Our aim is to find fraudulent transactions, help save money, avoid reputation damage and prevent money laundering.

The results are summarised in Fraud_Detection_ML_challenge.pdf

---

## Requirements and Environment

Requirements:
- pyenv with Python: 3.11.3

Environment: 

For installing the virtual environment you can either use the Makefile and run `make setup` or install it manually with the following commands: 

```Bash
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

## Usage

Data Inspection, EDA, Feature Engineering and Modeling were done in fraud_detection.ipynb. 



