# STGNN-Groundwater-Level-Prediction
An extensible spatiotemporal graph neural network framework for groundwater level prediction.

This repository provides the source code and test data for the manuscript:

**An extensible modeling framework based on spatiotemporal graph neural
network for groundwater level prediction: a case study in the middle
reaches of the Heihe River Basin**

## Quick Test

A reduced held-out test dataset and a trained model checkpoint are
provided for rapid verification of the proposed framework.

Open:

`01_quick_test_submission_v3.ipynb`

and run all cells from top to bottom.

The quick-test dataset is intended for software and inference
verification. It does not replace the complete dataset used to obtain
all quantitative results reported in the manuscript.

## Full Experiment

The complete experimental workflow is provided in:

`ST-GNN.ipynb`

## Requirements

Install the required Python packages using:

`pip install -r requirements.txt`

## Test Data

The reduced held-out test data are provided in:

`quick_test_assets/`

## Model Checkpoint

The trained model checkpoint used by the quick test is provided as:

`quick_test_assets/model_state_dict.pth`
