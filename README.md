# Adversarially Robust Deep Learning

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ashwiniii770/adversarial-robust-deep-learning/blob/main/adversarial_robust_dl.ipynb)

This project explores adversarial robustness in deep learning models.

## Overview

Deep learning models are vulnerable to adversarial attacks where small perturbations in input data can cause incorrect predictions.  
This project demonstrates how adversarial examples affect model performance and how adversarial training improves robustness.

## Features

- CNN model training using PyTorch
- Adversarial attack generation (FGSM / PGD)
- Robustness evaluation
- Adversarial training defense

## Tools Used

- Python
- PyTorch
- Google Colab
- Matplotlib

## Results

| Scenario | Accuracy |
|--------|--------|
| Clean Model | 27.62% |
| Under Adversarial Attack | 13.78% |
| After Adversarial Training | Improved robustness |

This experiment shows that adversarial attacks significantly degrade model performance and adversarial training helps improve robustness.

## How to Run

You can run the project directly in Google Colab using the button at the top.

Or run locally:

pip install torch torchvision matplotlib torchattacks

Then open the notebook:

jupyter notebook adversarial_robust_dl.ipynb

## Future Improvements

- Implement stronger attacks such as PGD or DeepFool
- Train deeper models like ResNet
- Improve visualization of adversarial examples
- Evaluate robustness on larger datasets

## Author

Ashwini
