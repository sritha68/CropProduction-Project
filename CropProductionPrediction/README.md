Crop Production Prediction using Rainfall Data 
This project predicts crop production based on rainfall and area using a Linear Regression model.
It aims to help in agricultural planning by analyzing the relationship between rainfall and crop yield.

TECHNOLOGIES USED:
1. Python 
2. Pandas
3. NumPy
4. Matplotlib / Seaborn
5. Scikit-learn (Linear Regression model)
6. Jupyter Notebook

DATASET INFORMATION:
1. Crop Production Data – contains information about crop yield, area, and production (from data.gov.in).
2. Rainfall Data – contains average annual rainfall for each state and year.

STEPS:
1. Data preprocessing (merging datasets)
   -Load rainfall and crop production data
   -Clean null values and convert data types
   -Merge datasets based on State and Year
2. Exploratory Data Analysis (EDA)
   -Visualize rainfall and crop production trends by state/year
   -Check correlation between rainfall and production
3. Model Building
   -Features: Rainfall, Area
   -Target: Production
   -Algorithm: Linear Regression
4. Model Evaluation
   -R² Score
   -Mean Absolute Error (MAE)
   -Mean Squared Error (MSE)
   -Actual vs Predicted Visualization

SAMPLE RESULTS:
| Metric | Value |
|---------|--------|
| R² Score | 0.79 |
| MAE | 120.54 |
| MSE | 25400.67 |

Accuracy(RSQUARE R^2 = 0.79)-> The model performs well and captures rainfall–production patterns effectively.

HOW TO RUN:
1. Clone this repository
   ```bash
   git clone https://github.com/<your-username>/CropProductionPrediction.git
   cd CropProductionPrediction
2. Install dependencies
   -pip install -r requirements.txt
3. Open Jupyter Notebook
   -jupyter notebook notebooks/Crop_Production_Prediction.ipynb
4. Run all cells to reproduce the results.   

FOLDER STRUCTURE:

CropProductionPrediction/
- notebooks/
  - Crop_Production_Prediction.ipynb
- data/
  - (sample datasets or README with dataset links)
- src/
  - train_model.py (optional)
- requirements.txt
- README.md
- .gitignore

Author
Sritha Chippa
B.Tech in Artificial Intelligence (2025)
Project: Crop Production Prediction using Rainfall Data
