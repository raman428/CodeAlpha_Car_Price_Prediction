# Car Price Prediction with Machine Learning

## Project Overview
This project predicts the selling price of used cars using Machine Learning algorithms. It analyzes car features such as present price, kilometers driven, fuel type, transmission, ownership and car age.

## Internship
CodeAlpha Data Science Internship

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Algorithms
1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor

## Model Evaluation

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 1.4725 | 2.5245 | 0.7527 |
| Decision Tree | 1.1085 | 2.1056 | 0.8280 |
| Random Forest | 1.4657 | 3.5094 | 0.5222 |

## Best Model
Decision Tree Regressor achieved the best R² score of 0.8280.

## Project Workflow
1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Data Encoding
6. Model Training
7. Model Evaluation
8. Car Price Prediction

## How to Run

Install dependencies:

```bash
pip install -r requirements.txt
```

Open Jupyter Notebook:

```bash
jupyter notebook
```

Open `car_price_prediction.ipynb` and run the cells.

## Conclusion
The project demonstrates how Machine Learning regression algorithms can be used to estimate used car selling prices. Among the three tested models, Decision Tree Regressor performed best on the test dataset.