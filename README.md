# 🧪 Molecular Solubility Prediction (ESOL Dataset)

This project predicts the **aqueous solubility of molecules** using different machine learning models.  
The dataset used is the **ESOL dataset**, which contains molecules with experimental solubility values.  

The goal is to evaluate multiple ML models (Linear Regression, Random Forest, XGBoost), perform **hyperparameter tuning**, and identify the best-performing model for solubility prediction.  

---

## 📂 Project Structure

1. **Load and Import Dataset**  
2. **Data Splitting**  
3. **Linear Regression**  
   - Predictions and Metrics  
   - Predicted vs Actual Plot  
4. **Random Forest Regressor**  
   - Predictions and Metrics  
   - Predicted vs Actual Plot  
5. **XGBoost Model**  
   - Train XGBoost  
   - Predictions and Metrics  
   - Predicted vs Actual Plot  
6. **Model Comparison**  
   - R² and MSE comparison plots  
7. **Hyperparameter Tuning for XGBoost**  
8. **Final XGBoost Model with Best Parameters**  
   - Predictions and Metrics  
   - Predicted vs Actual Plot  
9. **Baseline vs Tuned XGBoost Performance**  
   - Metrics comparison (table + plots)  
10. **Conclusion & Future Work**  

---

## ⚙️ Tech Stack

- **Python**
- **Scikit-learn** (Linear Regression, Random Forest, metrics, model selection)
- **XGBoost** (regression and tuning)
- **Matplotlib / Seaborn** (visualization)
- **Google Colab** (execution environment)

---

## 📊 Results

- **Linear Regression** → Weak performance (negative R²).  
- **Random Forest** → Better than baseline, moderate performance.  
- **XGBoost** → Outperformed other models.  
- **Tuned XGBoost** → Achieved the **best R² score** with optimized hyperparameters.  

Example metrics (fill with your values):  
| Model                   | R² Score  |   MSE   |
|-------------------------|---------: |--------: |
| Linear Regression       |   -3.1    |   19.5   |
| Random Forest           |    0.86   |   0.63   |
| XGBoost (Baseline)      |    0.89   |   0.47   |
| XGBoost (Tuned)         |    0.88   |   0.53   |

---

## 📈 Visualizations

- **Predicted vs Actual plots** for each model.  
- **Model comparison bar charts** (R², MSE).  
- **Baseline vs Tuned XGBoost plots** to highlight improvement.  

---

## 🚀 Future Work

- Try **Graph Neural Networks (GNNs)** for molecular property prediction.  
- Use **other chemical datasets** (LogP, FreeSolv, Lipophilicity).  
- Explore **deep learning approaches** with molecular fingerprints.  

---

## 👩‍💻 Author

- Project by Priyanka.
