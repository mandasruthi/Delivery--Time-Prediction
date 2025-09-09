# Delivery Time Prediction using Linear Regression

**Author:** M SRUTHI RAJ  
**Assignment:** Linear Regression — Parcel Delivery Time Estimation

---

## 📂 Project Structure
- `LR_Delivery_Time_Prediction_M_SRUTHI_RAJ.ipynb` → Final Jupyter notebook with code, analysis, and plots.  
- `LR_Delivery_Time_Prediction_M_SRUTHI_RAJ.pdf` → Concise PDF report with results and conclusions.  
- `porter_data_1.csv` → Dataset used for training and evaluation.  
- `outputs/` → Saved plots, selected features, and trained model artifacts.  
- `requirements.txt` → Python dependencies.  

---

## ⚙️ Methodology
1. **Data Preprocessing**
   - Missing value handling
   - Feature engineering (hour, weekday)
   - Encoding categorical features
   - Outlier capping and scaling  

2. **Modeling**
   - Baseline Linear Regression
   - Feature selection (top 12 features by coefficients)
   - Model evaluation (RMSE, MAE, R²)

3. **Diagnostics**
   - Residuals vs Predicted
   - QQ-plot
   - Feature importance analysis

---

## 📊 Results
- **Validation RMSE:** ~X minutes  
- **Validation R²:** ~Y  
- Key predictors: distance, dashers availability, market ID.  

---

## 📌 Assumptions
- Linear relationship between predictors and target.  
- Errors are independent & homoscedastic.  
- No severe multicollinearity.  
- Data is representative.  

---

## 💡 Business Recommendations
- Optimize dasher allocation during peak hours.  
- Establish micro-hubs for high-distance deliveries.  
- Predict SLA breaches & alert customers proactively.  
- Consider adding weather/traffic data for future improvements.  

---

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/Delivery-Time-Prediction.git
   cd Delivery-Time-Prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook LR_Delivery_Time_Prediction_M_SRUTHI_RAJ.ipynb
   ```

---
