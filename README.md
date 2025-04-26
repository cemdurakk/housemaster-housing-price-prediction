# 🏡 HouseMaster: Advanced Housing Price Prediction

This project aims to predict housing prices based on a real-world dataset using advanced machine learning techniques.

We applied a complete data science pipeline:
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering (Encoding, Scaling)
- Model Training & Evaluation (Linear Regression, Random Forest, XGBoost)
- Model Performance Comparison

## 📊 Models and Results

| Model | Training RMSE | Test RMSE |
|:------|:--------------|:----------|
| Linear Regression | ≈ 19,548 $ | ≈ 36,069 $ |
| Random Forest | ≈ 10,658 $ | ≈ 27,398 $ |
| XGBoost | ≈ 17,206 $ | ≈ 26,784 $ |

- **Best Model:** XGBoost  
- **Lowest Test Error:** ≈ $26,784

## 🚀 Technologies Used

- Python 3.11
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost

## 📂 Project Structure

```plaintext
├── data/
│   └── AmesHousing.csv
├── notebook.ipynb
├── README.md
├── requirements.txt
```

## 📝 Conclusion

XGBoost was the most effective model for predicting house prices, outperforming both Linear Regression and Random Forest. The model demonstrates strong generalization performance without severe overfitting.

---

## ✨ Future Work

- Hyperparameter tuning with GridSearchCV or RandomizedSearchCV
- Feature selection based on importance
- Ensemble methods like Stacking