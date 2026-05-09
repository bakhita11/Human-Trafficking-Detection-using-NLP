# Human Trafficking Detection using NLP and Transformers

This repository contains a transformer-based NLP pipeline for detecting potential human trafficking indicators in online advertisements.

The project focuses on semantic text analysis using DistilBERT and includes preprocessing, semantic grouping, weighted classification, threshold-based prediction, and evaluation utilities.

## Features

- DistilBERT-based text classification
- Semantic preprocessing pipeline
- TF-IDF semantic grouping
- Duplicate and near-duplicate filtering
- Weighted loss for class imbalance
- Threshold-aware prediction
- Precision-Recall analysis
- ROC analysis
- Confusion matrix generation
- Per-class evaluation metrics
- Group-aware train/validation/test splitting

## Dataset

The dataset contains approximately 3,000 publicly accessible online advertisements labeled as:

- Legitimate
- Potential Trafficking

The dataset was designed for controlled research experiments and semantic classification evaluation.

## Project Structure

```text
project/
│
├── data/
├── figures/
├── notebooks/
├── models/
├── results/
├── src/
└── README.md
Model
The primary model uses:
•	DistilBERT
•	Partial transformer fine-tuning
•	Weighted cross-entropy loss
•	Cosine learning-rate scheduling
•	Threshold-based classification
Evaluation Metrics
The system evaluates performance using:
•	Accuracy
•	Precision
•	Recall
•	Macro F1-score
•	Confusion Matrix
•	PR Curve
•	ROC Curve
Example Results
Metric	Score
Validation Accuracy	0.8867
Validation F1	0.8338
Requirements
Install dependencies:
pip install transformers scikit-learn torch pandas matplotlib
Usage
Run the training pipeline:
python train.py
Run evaluation:
python evaluate.py
Ethical Notice
This project is intended strictly for research and decision-support purposes.
The system should not be used as an autonomous enforcement tool. Human review and oversight are required for all operational use cases.
License
MIT License

Then on GitHub:

1. Click:

```text id="t9d2ks"
Add file → Create new file
2.	Name the file:
README.md
3.	Paste the content.
4.	Click:
Commit changes
Your repository will instantly look much more professional.

