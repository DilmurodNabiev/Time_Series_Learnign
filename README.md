# Time Series Learning (In Progress)

This repository explores fundamental methods for time series forecasting using both classical statistical models and deep learning techniques. The goal is to establish a comparative foundation between models like ARIMA and Recurrent Neural Networks (RNN) on time series data.

> ⚠️ **Note:** This is the **first experimental version** of the project.  
> As a result, accuracy is relatively low, and improvements are planned for upcoming versions.  
> The project is a work in progress and under active development.

---

## 📂 Contents

This repository includes the following notebooks:

- **`dl4_ARIMA.ipynb`**  
  Classical time series forecasting using the ARIMA model. Includes preprocessing, stationarity checks, model fitting, and evaluation.

- **`dl4_RNN.ipynb`**  
  A simple RNN-based model using TensorFlow/Keras to learn from time series data. Focuses on sequence generation, model training, and comparison with ARIMA.

---

## 📊 Objectives

- Understand and compare time series forecasting methods.
- Evaluate model performance on a common dataset.
- Establish a baseline for classical vs. deep learning methods.
- Iterate and improve model performance in future versions.

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/DilmurodNabiev/Time_Series_Learnign.git
cd Time_Series_Learnign
```
### 2. Install dependencies

```bash
pip install -r requirements.txt
```
Or manually install:
pandas, numpy, matplotlib, statsmodels, scikit-learn, tensorflow, keras

### 3. Run notebooks

```bash
jupyter notebook dl4_ARIMA.ipynb
jupyter notebook dl4_RNN.ipynb
```
## Future Improvements

* Refactor code for modularity and reusability.

* Tune hyperparameters and add regularization to neural networks.

* Try GRU and Transformer-based models.

* Extend to multivariate time series data.

* Integrate more robust evaluation metrics and visualization tools.

