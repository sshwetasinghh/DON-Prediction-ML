# DON Prediction using Machine Learning  

##  Project Overview  
This project builds a **machine learning pipeline** to predict **DON (Deoxynivalenol) concentration** in corn samples using **hyperspectral imaging data**.
The final model is a **Random Forest Regressor**, fine-tuned for optimal performance.  

## Dataset  
- Features: Spectral reflectance values across multiple wavelengths.  
- Target: DON concentration (a continuous numerical value).  
- Preprocessing: Handled missing values, removed outliers (DON > 20,000 ppb), and normalized spectral bands.  

##  Model Training & Evaluation  
- **Baseline Model:** Random Forest Regressor  
- **Hyperparameter Tuning:** Performed using `RandomizedSearchCV`  
- **Evaluation Metrics:**  
  - Mean Absolute Error (MAE)  
  - Root Mean Squared Error (RMSE)  
  - R² Score  

##  Results & Visualizations  
- Scatter plot of **actual vs. predicted DON values**.  
- Feature importance analysis using **SHAP**.  

