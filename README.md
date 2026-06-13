# Heart Disease Prediction

This project is based on predicting heart disease using machine learning. The dataset contains different health related parameters of patients, and the target variable shows whether heart disease is present or not.

The main aim of this project is to analyze the dataset, train different machine learning models, and compare the results.

## Machine Learning Algorithms Used

1. Logistic Regression
2. K-Nearest Neighbours
3. Decision Tree
4. Random Forest
5. Support Vector Machine

## Accuracy

The best accuracy was achieved using Random Forest.

## Dataset

The dataset used in this project is `heart.csv`.

It contains columns such as age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, maximum heart rate, and target.

## Files

- `data/heart.csv` - dataset
- `notebooks/heart_disease_prediction.ipynb` - Jupyter notebook
- `models/best_model.pkl` - saved machine learning model
- `models/scaler.pkl` - saved scaler
- `requirements.txt` - required Python libraries

## How to Run

Clone the repository:

```bash
git clone https://github.com/ayesha-naaz27/heart-disease-prediction.git
```

Go to the project folder:

```bash
cd heart-disease-prediction
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook notebooks/heart_disease_prediction.ipynb
```

## Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- joblib
