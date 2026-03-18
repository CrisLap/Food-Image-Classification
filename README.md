# GourmetAI – Production-Grade Food Image Classification

Advanced deep learning workflow for food image classification using PyTorch and Optuna.

## Project Overview

This project implements a complete AI engineering pipeline for food image classification using deep learning, including:

- Data augmentation and preprocessing
- Transfer learning with pre-trained models
- Optuna hyperparameter optimization
- Train/validation/test splitting and evaluation
- Inference demo and visualization

## Setup

### Prerequisites

- Python 3.8+
- pip

### Install Dependencies

```bash
pip install -r requirements.txt

### Dataset
The notebook downloads and extracts the dataset from:

dataset_food_classification.zip

This archive should be placed in the project root (or will be auto-downloaded by the notebook).

### Running the Notebook
Open and run:


jupyter notebook gourmetai.ipynb
Run the cells in order to:

Download/extract the dataset
Perform EDA
Train the model with Optuna tuning
Evaluate performance and run inference