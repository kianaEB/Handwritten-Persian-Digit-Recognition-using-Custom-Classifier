# Handwritten Persian Digit Recognition - Custom Classifier

Recognizes handwritten Persian (Farsi) digits with a from-scratch Minimum Distance Classifier - no black-box ML model.

## Overview
Implements a custom Minimum Distance Classifier and applies it to the Hoda handwritten-digit dataset (the standard Farsi digit benchmark), demonstrating the classifier mechanics end-to-end.

## Approach
1. **Load & preprocess** the Hoda digit images (normalize, flatten/feature-prep).
2. **Build class prototypes** - compute a representative (mean) vector per digit class.
3. **Classify** each test image by assigning it to the nearest class prototype (minimum distance).
4. **Evaluate** classification accuracy across the 10 digit classes.

## Tech stack
Python, NumPy, Pandas. Jupyter Notebook. (Classifier implemented from scratch - no scikit-learn model.)

## Repo contents
- `HodaDigitRecognition.ipynb` - data loading, custom classifier, evaluation.

## Run it
```
pip install numpy pandas
jupyter notebook
```
