# EuroSAT - Classification Metrics and Model Evaluation

Satellite classification evaluation using confusion matrices, precision, recall, macro-F1 and spatial data leakage analysis.

## Overview

This project is part of a three-stage research initiative on
satellite imagery, geospatial intelligence and responsible AI.

Using the EuroSAT dataset, we explore how machine learning
can contribute to environmental monitoring, agriculture
and evidence-based decision-making.

## Research objectives

Precision, recall, F1-score, confusion matrices, error analysis, class imbalance and spatial leakage.

## Technologies

Python, Jupyter Notebook, PyTorch, scikit-learn,
computer vision and remote sensing.

## Dataset

EuroSAT contains approximately 27,000 Sentinel-2 images
across 10 land-use and land-cover classes.

Original publication:
https://doi.org/10.1109/JSTARS.2019.2918242

Dataset:
https://github.com/phelber/EuroSAT

## Run in Google Colab

[Open notebook](https://colab.research.google.com/github/CarlosSanchezGutierrez/eurosat-classification-metrics/blob/main/notebook.ipynb)

Use a GPU runtime for training experiments when required.
Execute all cells sequentially and inspect the results.

## Engineering principles

- Reproducible experiments
- Explicit assumptions and limitations
- Transparent evaluation metrics
- Responsible data governance
- Independent model validation
- Evidence-based technical decisions

## Limitations

High overall accuracy does not guarantee balanced class-level performance or geographic generalization.

Model performance should not be presented as operationally
validated until the experiments are fully executed and tested.

## Related research

- [S1 - Exploratory Analysis](https://github.com/CarlosSanchezGutierrez/eurosat-sentinel2-exploratory-analysis)
- [S2 - Transfer Learning](https://github.com/CarlosSanchezGutierrez/eurosat-resnet18-transfer-learning)
- [S3 - Classification Metrics](https://github.com/CarlosSanchezGutierrez/eurosat-classification-metrics)

## Author

Carlos Sanchez Gutierrez

Computer Science and Technology Engineering

Tecnologico de Monterrey

GitHub: https://github.com/CarlosSanchezGutierrez

Website: https://carlossanchezgutierrez.com

## Research philosophy

Reliable artificial intelligence requires more than
predictive accuracy. It requires transparency, rigor,
reproducibility and responsibility toward the people
and environments affected by technological decisions.