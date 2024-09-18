# Mushroom Edibility Classification

## Overview

This project classifies mushrooms as either edible or poisonous using a **Logistic Regression** model. By analyzing various features such as the shape, color, and habitat of mushrooms, the model predicts whether a mushroom is safe to eat or poisonous.

The classification is based on the **Mushroom Dataset** from the UCI Machine Learning Repository, which contains 8,000+ mushroom samples and 23 categorical features. The target variable indicates whether a mushroom is edible (`e`) or poisonous (`p`).

---

## Table of Contents

- [Project Overview](#overview)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Project Structure](#project-structure)
- [Setup](#setup)
- [Usage](#usage)
  - [Training the Model](#training-the-model)
  - [Saving the Model](#saving-the-model)
  - [Loading and Using the Model](#loading-and-using-the-model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

---

## Dataset

The dataset used for this project can be downloaded from the [UCI Mushroom Dataset](https://archive.ics.uci.edu/ml/datasets/mushroom). It contains 8,124 samples of mushrooms, where each sample has 23 categorical features describing the mushroom (e.g., cap shape, gill color, stalk surface) and one target variable (`class`), which indicates whether the mushroom is edible (`e`) or poisonous (`p`).

---

## Requirements

The project uses the following libraries and dependencies:

- Python 3.x
- Jupyter Notebook (optional, for running the notebook interactively)
- Libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`
  - `pickle` (for saving and loading models)
  
Install the required Python libraries using `pip`:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
