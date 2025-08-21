

## GEOmine

## Overview
GeoMine is a **Geospatial Intelligence System** designed to detect mineral resources by processing satellite imagery and geospatial datasets using **Machine Learning** and **Dimensionality Reduction** techniques.

## Data
- **Geospatial Datasets:** Satellite imagery, remote sensing data, geological survey data  
- **Data Format:** GeoTIFF, Shapefiles, CSV  
- **Features:**  
  - Spectral bands  
  - Geological attributes  
  - Terrain & topographic indicators  

## Approach
### 1. Data Preprocessing
- Cleaning and standardizing geospatial data  
- Extracting key features for analysis  

### 2. Dimensionality Reduction (PCA)
- Reduces redundancy in large datasets  
- Retains the most significant features  

### 3. Model Selection
- Classification algorithms tested: **Random Forest, SVM, XGBoost**  
- Evaluation metrics: **Accuracy, Precision, F1-score**  
- Final algorithm chosen based on best performance  

### 4. Visualization & Validation
- Mapping results to geospatial layers  
- Validating with historical mineral data  
<img width="1018" height="678" alt="Screenshot 2025-06-11 203017" src="https://github.com/user-attachments/assets/7f0f496a-bb9e-47f1-9659-f5cdbee3481d" />

## Tech Stack
- **Python:** NumPy, Pandas, Scikit-learn  
- **Geospatial Libraries:** GDAL, GeoPandas, Rasterio  
- **Visualization:** Matplotlib, Seaborn  

## How to Run
```bash
git clone https://github.com/prajesdas/GeoMine.git
cd GeoMine
pip install -r requirements.txt
python main.py
````

## License

This project is licensed under the **MIT License**.


