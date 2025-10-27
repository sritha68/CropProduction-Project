                  **Crop Production Prediction using Rainfall and Area**

This project predicts **crop production** based on **rainfall** and **cultivated area** using a **Linear Regression Machine Learning model**.  
It aims to help understand how environmental and land factors influence crop yield in different Indian states.

---
Project Overview:
Agriculture in India heavily depends on rainfall.  
This project combines **crop production data** and **rainfall data** to build a model that predicts crop production.  

I used:
- Crop Production Dataset (from [data.gov.in](https://data.gov.in/) / Kaggle)
- Rainfall Dataset (state-wise yearly rainfall)
- Linear Regression Model from `scikit-learn`

---
Steps Followed:
1. Data Collection
- Crop production data (State, Year, Crop, Area, Production)
- Rainfall data (State, Year, Rainfall)
- Merged on **State** and **Year** columns
2. Data Preprocessing
- Removed missing/null values
- Converted columns to numeric
- Selected relevant features: `Rainfall`, `Area`, and `Production`
3. Model Building
- **Independent variables (X):** Rainfall, Area  
- **Dependent variable (y):** Production  
- Algorithm: **Linear Regression**
4. Model Training
- Split data into 80% training and 20% testing
- Trained using `LinearRegression()` from `sklearn`
5. Model Evaluation
- **R² Score:** 0.79  
- **Mean Absolute Error (MAE):** *your value here*  
- **Mean Squared Error (MSE):** *your value here*  
- Visualized **Actual vs Predicted Production**

---
Results:

| Metric | Value |
|---------|--------|
| R² Score | 0.79 |
| MAE | (fill your value) |
| MSE | (fill your value) |

Visualization:
The following scatter plot compares **Actual vs Predicted Crop Production**


---
Tech Stack:
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn (sklearn)
- Jupyter Notebook

---
Project Structure:

CropProductionProject/
├─ notebooks/
│ └─ CropProduction.ipynb
├─ data/
│ └─ README.md
├─ requirements.txt
├─ README.md
└─ .gitignore


---
Installation & Usage
1. Clone the repository
bash
-git clone https://github.com/<sritha68>/CropProductionProject.git
2. Navigate to Repository
-cd CropProductionProject
3. Install dependencies
-pip install -r requirements.txt
4. Run the notebook
-notebooks/Project1.ipynb

Data Information:
You can download the datasets from:
Crop Production Data — data.gov.in
Rainfall Data — data.gov.in

Future Work:
Try different models (Random Forest, Decision Tree)
Add temperature and soil fertility data
Build a web app for farmers to predict yields interactively

