# 🌾 Crop Recommendation System

This project is a machine learning-based **Crop Recommendation System** designed to suggest the most suitable crop to cultivate based on various environmental and soil parameters.

## 📊 Dataset

- **Shape:** (2200, 9)
- **Features:**
  - `N`: Nitrogen content in the soil
  - `P`: Phosphorous content in the soil
  - `K`: Potassium content in the soil
  - `temperature`: Temperature in degree Celsius
  - `humidity`: Relative humidity in %
  - `ph`: pH value of the soil
  - `rainfall`: Rainfall in mm
  - `label`: Target label indicating the crop name

## 🤖 Models Used

Three classification models were trained and evaluated on the dataset:

1. **Random Forest Classifier**
   - **Accuracy:** `99.31%`
   - Robust and highly accurate ensemble model.

2. **Decision Tree Classifier**
   - **Accuracy:** `98.41%`
   - Simple and interpretable tree-based model.

3. **K-Nearest Neighbors (KNN)**
   - **Accuracy:** `97.05%`
   - Distance-based model that performs well with properly scaled data.

## ✅ Results

| Model                   | Accuracy       |
|------------------------|----------------|
| Random Forest Classifier | 99.31%        |
| Decision Tree Classifier | 98.41%        |
| K-Nearest Neighbors      | 97.05%        |

The **Random Forest Classifier** delivered the highest performance and is recommended as the final model for deployment.

## 📌 Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

You can install the dependencies using:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
