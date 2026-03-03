#STATS 507 Final Project: Credit Card Fraud/Anomaly Detection

**Author:** Arnav Mehra
**Email:** arnmehra@umich.edu

## Project Overview

Machine learning for credit card fraud and anomaly detection. Includes data extraction using SQL alongside predictive modeling using Python. Developed as part of my Master's in Applied Statistics at the University of Michigan.

**Key Results:**
- Logistic Regression: 75.70% recall (fraud detection rate), 2% precision
- Random Forest: 71.71% recall, 98% precision
- Isolation Forest: 1.19% recall , 1% precision (shows unsupervised limitations)

## Files

- `STATS 507_Final Project_Credit Card Anomaly Detection.ipynb` - Complete project code
- `STATS 507_Final Project_Credit Card Anomaly Detection.pdf` - 2-page project report
- `requirements.txt` - Python dependencies

## Data Setup

**Dataset:** [Credit Card Transactions](https://huggingface.co/datasets/pointe77/credit-card-transaction)

## Running the Project
```bash
# Install dependencies
pip install -r requirements.txt

# Run Jupyter notebook
jupyter notebook STATS 507_Final Project_Credit Card Anomaly Detection.ipynb
```

## Results Summary

See `STATS 507_Final Project_Credit Card Anomaly Detection.pdf` for detailed analysis.

| Model | Recall | Precision |
|-------|--------|-----------|
| Logistic Regression | 75.70% | 2% |
| Random Forest | 71.71% | 98% |
| Isolation Forest | 1.19% | 1% |
