# Diabetes Prediction with Decision Tree Regressor


## Project Overview
This project applies a **Decision Tree Regressor** to the **Diabetes dataset** to predict disease progression based on clinical features.  
It demonstrates:
- How decision trees can be applied for regression tasks  
- The effect of hyperparameter tuning  
- Evaluation using regression performance metrics  


## Dataset
- **Source**: Scikit-learn Diabetes Dataset
- **Samples**: 442 patients  
- **Features** (10 clinical measurements):  
  - Age  
  - Sex  
  - BMI  
  - Blood Pressure  
  - 6 Serum Measurements  
- **Target**: Continuous value — disease progression one year later  


## Workflow
1. **Data Loading** → Load dataset using `load_diabetes()`  
2. **Preprocessing & EDA** → Explore distributions, correlations, and feature-target relationships  
3. **Model Training** → Train a baseline `DecisionTreeRegressor`  
4. **Hyperparameter Tuning** → Optimize with parameters like:  
   - `max_depth`  
   - `min_samples_split`  
   - `min_samples_leaf`  
   - `criterion` (MSE, MAE)  
   - Tuned using **GridSearchCV**  
5. **Evaluation** 
   - R² Score  
   - Mean Absolute Error (MAE)  
   - Mean Squared Error (MSE)  


## Results
- **Baseline Model**: Captured general patterns but tended to overfit  
- **After Tuning**:  
  - Higher R² Score (better explained variance)  
  - Lower MAE and MSE (improved prediction accuracy)  
