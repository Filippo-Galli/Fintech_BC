# Final Project: Advanced Anomaly Detection in Finance

This folder contains the final project for the FinTech course, focused on advanced anomaly detection and time series modeling in financial markets. The project leverages deep learning and statistical techniques to identify anomalous periods (such as market stress events) using real-world financial data.

## Contents

- **anoGAN.ipynb**: Implementation of Generative Adversarial Networks (GANs) for anomaly detection in time series data.
- **Autoencoder.ipynb**: Autoencoder-based approach for unsupervised anomaly detection.
- **BNN.ipynb**: Bayesian Neural Network for probabilistic modeling and uncertainty estimation.
- **LSTM.ipynb**: Long Short-Term Memory (LSTM) neural network for sequence modeling and classification of anomalies.
- **baseline models.ipynb**: Baseline models and traditional machine learning approaches for comparison.
- **data/**: Contains the dataset (`Dataset4_EWS.xlsx`) used for all experiments, including market and macroeconomic indicators and anomaly labels.

## Dataset
- The dataset consists of weekly observations of market and macroeconomic indicators, with a response variable indicating anomalous periods.
- Data is sourced from Bloomberg and is used for both training and evaluation of models.

## How to Use
1. Open any of the notebooks in this folder to explore different modeling approaches.
2. Each notebook is self-contained, with code for data loading, preprocessing, model training, and evaluation.
3. The `data/` folder contains all necessary data files.

## Requirements
- Python 3.x
- Jupyter Notebook
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, tensorflow/keras, pytorch, etc.

Install dependencies with:
```bash
pip install -r requirements.txt
```

## Project Highlights
- Comparison of deep learning models (GANs, Autoencoders, LSTM, BNN) for anomaly detection.
- Emphasis on handling class imbalance and evaluating model performance with real-world financial data.
- Modular and extensible code for further experimentation.

---

For questions or suggestions, feel free to open an issue or contribute!
