K-Nearest Neighbours Plant Suitability Classifier

## Overview

This project implements a K-Nearest Neighbours (KNN) classification algorithm from scratch using pylab.

The model determines whether Date Palms or Watercress is more suitable based on environmental and water conditions.

It uses:

* Euclidean distance
* Z-score feature scaling
* k = 5 nearest neighbours
* Majority voting classification

## Problem Statement

Given environmental conditions:

* Salinity
* pH level
* Temperature
* Calcium (Ca²⁺) concentration

The algorithm aim predicts the most suitable plant species given these factors. Given the time constraints and it was a hackathon, we limited it to two plants. 

## Dataset

The dataset is embedded directly in the script.

Each data entry contains:

```
[salinity, pH, temperature, Ca2+ concentration, plant_label]
```

## How to Run

1. Run the script:
```
python knn_classifier.py
```

2. You will be prompted to enter:

* Salinity level
* pH level
* Temperature
* Calcium concentration
