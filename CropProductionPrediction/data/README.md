This folder contains information about the datasets used for the Crop Production Prediction project.
DATASET DESCRIPTION:
I used two datasets:
1. Rainfall Data — contains information about annual or seasonal rainfall (in mm) for different states and years.
2. Crop Production Data — contains details about crop name, area of cultivation, and production.

DATA PREPARATION STEPS:
1. Both datasets were cleaned and merged using the common columns (like State, Year).
2. Missing values in the "Area" column were handled appropriately.
3. Selected features:
   - Rainfall
   - Area
   - Production (target)

NOTE:
Large raw CSV files are not included in this repository to avoid large file sizes.  
If you want to run the project locally:
- Download the datasets from the below sources  
- Place them in this `/data` folder.

Download Links:
- [Rainfall Dataset](https://data.gov.in)
- [Crop Production Dataset](https://data.gov.in)
