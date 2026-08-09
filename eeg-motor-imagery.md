# EEG Motor Imagery & Feature Selection

## Overview

A research-oriented machine learning project investigating feature selection for EEG-based motor imagery classification.

The project combines signal-derived EEG features with graph-based methods to investigate whether spatial relationships between EEG channels can improve feature selection and interpretability.

## Problem

EEG datasets can contain a very large number of features across channels and frequency bands. Selecting informative features is therefore important for reducing dimensionality, improving model performance, and making the selected patterns easier to interpret.

## Approach

The project explored:

- EEG frequency-band features
- Channel-level spatial relationships
- Laplacian Score
- Joint Laplacian Score (JLS)
- Spatial graph fusion
- Kronecker-product graph expansion
- Motor-area weighting / spatial priors
- SVM classification
- Feature-count experiments
- Cross-method comparisons

## EEG Frequency Bands

- Delta
- Theta
- Alpha
- Beta
- Gamma

## Feature Selection Methods Compared

- Laplacian Score
- Joint Laplacian Score
- RFE
- Mutual Information
- SelectKBest
- F-test
- Other graph-based feature-selection approaches explored during the research

## Evaluation

The analysis included:

- Accuracy vs. number of selected features
- Accuracy distributions
- Selected-feature/channel distributions
- Spatial/topographic interpretation
- Comparison of different graph-fusion parameters

## Technologies

Python, NumPy, pandas, scikit-learn, Matplotlib

## Research Context

This work formed the basis of my master's thesis work in EEG and Brain-Computer Interfaces and was also connected to conference/journal-oriented research.

> Raw/private datasets are not included in this public portfolio. Reproducible examples and figures can be added where permitted.
