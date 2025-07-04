# 🏡 House Price Prediction Using Linear Regression

This project predicts the **sale prices of houses** using a simple **Linear Regression** model. The model is trained on a dataset that includes features like **square footage**, **number of bedrooms**, and **total number of bathrooms**.

---

## 📁 Dataset

* **train.csv** — Used to train the model (includes actual SalePrice)
* **test.csv** — Used for prediction (SalePrice not provided)
* Dataset format is based on the classic **Kaggle House Prices** competition.

---

## 📊 Features Used

The model uses the following features:

* `GrLivArea` — Ground living area (square footage)
* `BedroomAbvGr` — Number of bedrooms above ground
* `TotalBathrooms` — Custom feature combining:

  * FullBath + 0.5 × HalfBath
  * BsmtFullBath + 0.5 × BsmtHalfBath

---

## 🧠 Model

* Model: **Linear Regression** (from scikit-learn)
* Libraries used: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

---

## ⚙️ How to Run

1. Clone the repo or open the notebook in Google Colab.
2. Ensure `train.csv` and `test.csv` are in your working directory.
3. Run the notebook to:

   * Train the model on `train.csv`
   * Predict `SalePrice` for `test.csv`
   * Save predictions to `submission.csv`

---

## 📈 Model Evaluation

Model performance on training data:

| Metric   | Value       |
| -------- | ----------- |
| MSE      | *123456.78* |
| RMSE     | *351.37*    |
| R² Score | *0.87*      |

*(Values are examples — update with your actual results)*

---

## 📝 Output

The final output is a file named **`submission.csv`** containing:

| Id   | SalePrice |
| ---- | --------- |
| 1461 | 208514.75 |
| 1462 | 187260.42 |
| ...  | ...       |

This file is ready to submit to Kaggle or for your internship review.

---

## 📌 Notes

* Missing values were handled using `.fillna()`.
* Visualizations include:

  * Actual vs Predicted prices
  * Error distribution
* You can improve the model by adding more features or using advanced regression models.

---

## 🙋‍♂️ Author

* Name: *Krishna Chopra*
* Internship Project — July 2025

---
