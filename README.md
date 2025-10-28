# 📊 Electricity Demand Forecasting Using Machine Learning Models

## 📌 Description  
Electricity demand is a fundamental pillar of the economy, presenting major challenges due to its difficult storage and high variability.  
With the rise of **Big Data** and **Artificial Intelligence**, advanced models have been developed to predict consumption and prevent economic losses.  
This project compares **Machine Learning** techniques and traditional models to evaluate their effectiveness in forecasting electricity demand.

---

## 🛠️ Technologies Used  

### 📌 Programming Language  
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### 📌 Main Libraries  
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)  
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)  
![Scikit-Learn](https://img.shields.io/badge/Scikit%20Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)  
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white)  
![Skforecast](https://img.shields.io/badge/Skforecast-FF6F00?style=for-the-badge&logo=python&logoColor=white)  
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)  
![Pyesios](https://img.shields.io/badge/Pyesios-003B57?style=for-the-badge&logo=python&logoColor=white)  

---

## 📂 Project Structure  

📁 **latex/** → Contains the thesis report written in LaTeX.  

📁 **preprocessing/** → Data extraction, preprocessing, and exploratory analysis.  
  - 📄 `extracción_temperatura_humedad.ipynb` → Retrieval of meteorological data.  
  - 📄 `datos_climáticos_diarios.csv` → Processed weather data.  
  - 📄 `extracción_demanda_eléctrica.ipynb` → Retrieval of electricity demand data.  
  - 📄 `datos_demanda_media_diaria.csv` → Daily average electricity consumption data.  
  - 📄 `preprocesamiento.ipynb` → Data cleaning and transformation.  
  - 📄 `datos_preprocesados.csv` → Final dataset ready for modeling.  
  - 📄 `EDA.ipynb` → Exploratory data analysis.  

📁 **models/** → Implementation and evaluation of forecasting models.  
  - 📄 `ARIMAX.ipynb` → Optimized ARIMAX model.  
  - 📄 `generic_model.ipynb` → **Decision Tree, Random Forest, and XGBoost** models.  
  - 📄 `LSTM.ipynb` → **LSTM Neural Network** for time series forecasting.  
  - 📄 `results.xlsx` → Model performance comparison.  

📁 **data/** → Backup folder containing raw and processed data files.  

---

## 🚀 Implemented Models  
✔ **ARIMAX** → Traditional statistical model for time series forecasting.  
✔ **Decision Tree, Random Forest, XGBoost** → Supervised machine learning algorithms.  
✔ **LSTM (Long Short-Term Memory)** → Neural network for sequential and temporal data.  

---

## 📈 Results and Conclusions  
This project analyzed and compared different **Machine Learning** models for electricity demand forecasting, highlighting **XGBoost** as the most efficient in terms of accuracy and computational cost.  
Although the **LSTM** model showed strong potential, its performance was limited by processing times and data granularity.  
Exogenous variables such as **temperature** and **holidays** played a key role in improving prediction accuracy, while others, like **humidity**, introduced some noise.  

Overall, the project successfully achieved its objectives, demonstrating the advantages of machine learning for time series forecasting. Future improvements could focus on using higher-resolution data and advanced hyperparameter optimization to further enhance model performance.

---


