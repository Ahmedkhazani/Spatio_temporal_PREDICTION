# Spatio-Temporal Air Quality Modeling

This project focuses on applying both traditional machine learning and time series models to predict air pollution levels (e.g., PM2.5 concentrations) using spatio-temporal data.

## 📁 Project Structure

- `Spatio_Temporel.ipynb`: Main Jupyter Notebook containing data preprocessing, model training, and evaluation
- `data.csv`: Dataset used (not included in this repo—please ensure it's in the same directory)
- `requirements.txt`: List of Python dependencies

## 🔍 Methods Used

- **Data Cleaning and Processing**
- **Machine Learning Models**
  - Random Forest
  - XGBoost
  - LightGBM
  - SVM
  - Logistic Regression
  - MLP (Multi-Layer Perceptron using Keras)
- **Time Series Modeling**
  - ARIMA (via `statsmodels`)
  - Auto ARIMA (via `pmdarima`)
- **Evaluation**
  - Accuracy
  - RMSE

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/spatio-temporel-modeling.git
   cd spatio-temporel-modeling
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Make sure `data.csv` is present in the root directory.

4. Run the notebook:
   ```bash
   jupyter notebook Spatio_Temporel.ipynb
   ```

## 📌 Notes
- This project is a work-in-progress.
- Dataset is assumed to be local; modify the path as necessary.
- Deep learning model (MLP) is implemented using Keras with TensorFlow backend.
- Feel free to contribute or suggest improvements.

## 📧 Contact
For questions or collaborations, please contact [your.email@example.com].
