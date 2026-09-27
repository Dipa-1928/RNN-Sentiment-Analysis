# Sentiment Analysis using RNN

This project implements **sentiment analysis using a Recurrent Neural Network (RNN)**.

## Overview

The notebook contains the complete workflow for the sentiment-analysis experiment, including data preparation, text preprocessing, model construction, training, and evaluation.

## Project Details

| Component | Details |
|---|---|
| Model | RNN |
| Framework | PyTorch |
| Dataset | IMDb movie reviews |
| Epochs | 10 |\n| Batch Size | 64 |\n
## Workflow

```text
Dataset
   ↓
Text Preprocessing
   ↓
Tokenization / Encoding
   ↓
Sequence Preparation
   ↓
RNN Model
   ↓
Training
   ↓
Evaluation
   ↓
Sentiment Prediction
```

## Files

```text
RNN-Sentiment-Analysis/
│
├── RNN_Sentiment_Analysis.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## How to Run

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd RNN-Sentiment-Analysis
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Open the notebook

Open:

```text
RNN_Sentiment_Analysis.ipynb
```

The notebook can be run using Jupyter Notebook, JupyterLab, or Google Colab.

## Results

The original notebook contains the recorded training/evaluation outputs and visualizations. These have been preserved in the GitHub-ready notebook.

## Technologies

- Python
- RNN
- PyTorch

## Note

The repository contains the notebook and project documentation. Dataset files are not included unless they were explicitly part of the original notebook workflow.
