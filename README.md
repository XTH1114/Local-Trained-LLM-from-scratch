# Local-Trained-LLM-from-scratch

This repository contains the necessary files and instructions to train a small Language Model (LLM) from scratch on your local machine using an external dataset. The `training.ipynb` Jupyter Notebook file walks you through the process step-by-step, enabling you to build and experiment with a foundational LLM for various natural language processing tasks. Codes are based on STAT 8931 at UMN.

## Overview

In this project, we train a small LLM model from scratch, which can be useful for learning about the model training process, experimenting with different architectures, or creating a model fine-tuned for a specific domain. This model is trained locally, without relying on external APIs or cloud services.

The main steps for training this model include:
- Preprocessing a dataset to make it compatible with the LLM architecture.
- Defining a small transformer-based model.
- Training the model on a local machine using PyTorch or TensorFlow (depending on the setup).
- Evaluating and testing the model's performance.

## Requirements

To train this model locally, ensure you have the following installed:

- Python 3.8 or later
- Jupyter Notebook or JupyterLab
- PyTorch or TensorFlow (depending on the chosen framework)
- Hugging Face Transformers library (optional, if using their utilities)
- Additional packages: numpy, pandas, matplotlib
