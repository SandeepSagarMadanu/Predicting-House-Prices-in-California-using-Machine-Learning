# Predicting-House-Prices-in-California-using-Machine-Learning
  

## Overview  
A machine learning project to **predict house prices in California** using the California Housing dataset.  
The project explores key factors such as **income, location, and space efficiency** to understand what drives housing prices.  

---

## Key Insights  
- **Median Income** is the strongest predictor of house prices (correlation ~0.7)  
- **Location matters** → Homes near the coast are more expensive  
- **Rooms per household** impacts price more than total room counts  

---

## Workflow  
- **Step 1:** Data exploration & visualization  
- **Step 2:** Preprocessing (scaling, handling missing values)  
- **Step 3:** Model building (Linear Regression, Decision Tree, Random Forest)  
- **Step 4:** Evaluation (R², MAE, RMSE)  

---

## Results  
- **Random Forest Regressor performed best**  
- The model shows that **income, location, and space efficiency** are the biggest drivers of California housing prices  

---

## Run the Project  
```bash
# Clone the repository
git clone https://github.com/your-username/California-House-Price-Prediction.git
cd California-House-Price-Prediction

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook Predicting_House_Prices_in_California_using_Machine_Learning.ipynb
