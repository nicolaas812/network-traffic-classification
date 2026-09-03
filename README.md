# Network Traffic Classification

This repository contains the implementation for an assignment comparing
k-nearest neighbours and classification trees for network traffic
classification.

The analysis uses the supplied UNSW-NB15 network traffic dataset and
compares the two classifiers using stratified five-fold cross-validation.

## Models

- k-nearest neighbours
- Classification tree

## Main evaluation measure

Macro-averaged F1-score is used as the primary performance measure because
the target classes are imbalanced.

## Files

- `assignment2_final_notebook.ipynb` - complete Python implementation and analysis

## Software

The implementation uses Python with pandas, NumPy, scikit-learn and matplotlib.
