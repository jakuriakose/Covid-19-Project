# 🦠 COVID-19 Mortality Risk Prediction

## 📌 About
A full end-to-end machine learning pipeline to predict 
COVID-19 mortality risk using patient data including 
pre-existing health conditions such as diabetes, 
pneumonia, hypertension, and more.

## 🛠️ Tools & Technologies
- Python
- Scikit-learn
- Random Forest Classifier
- Pandas
- NumPy
- Matplotlib

## 🔄 Pipeline
The project is split into 4 stages:
1. **Data Cleaning** - Removing invalid records
2. **Fill Missing Values** - Mode imputation grouped by age
3. **Mortality Risk Prediction** - ML model training
4. **Visualization** - Mortality distribution analysis

## 📊 Results
- Achieved **86.7% accuracy** in mortality risk prediction
- Analyzed **1M+ patient records**
- Identified key risk factors using feature importance
- Visualized mortality distribution by age group 
  and health conditions

## 🚀 How to Run
1. Clone the repository
2. Install dependencies:
   pip install -r requirements.txt
3. Run notebooks in order:
   - 1_Data_Cleaning.ipynb
   - 2_Fill_Missing_Values.ipynb
   - 4_Mortality_Risk_Prediction.ipynb
   - Prediction_Mortality_Risk_Visualization.ipynb
