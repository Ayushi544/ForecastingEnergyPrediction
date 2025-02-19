# Energy Consumption Forecasting System
## **Overview**  
This project predicts **energy consumption trends** using **time series forecasting models (ARIMA, SARIMA, and TBATS)**. It provides insights into future energy demands, helping optimize energy usage. The solution includes **data preprocessing, machine learning models, a Streamlit web app, and a Power BI dashboard** for interactive visualizations.  
## **Project Structure**  
📂 **Expanded_Data.csv** – Processed dataset with real & synthetic energy data.  
📂 **Synthetic_Data_Generation.ipynb** – Generates additional data by adding noise for better model performance.  
📂 **Data_Preprocessing_and_Models.ipynb** – Performs **EDA, feature engineering, and trains ARIMA, SARIMA, and TBATS models**.  
📂 **Streamlit_Webpage.py** – A user-friendly **web interface** to input parameters and view predictions dynamically.  
📂 **Power_BI_Dashboard.pbix** – A comprehensive **dashboard for energy consumption insights and forecasting trends**.  

## **Technologies Used**  
🔹 **Python (Pandas, NumPy, Scikit-learn, Statsmodels, Matplotlib, Seaborn)**  
🔹 **Machine Learning Models – ARIMA, SARIMA, TBATS**  
🔹 **Power BI for Interactive Data Visualization**  
🔹 **Streamlit for Web App Deployment**  

## **Key Features**  
✅ **Data Preprocessing** – Handles missing values, outliers, and scales data for better model accuracy.  
✅ **Forecasting Models** – ARIMA for baseline, SARIMA for seasonality, TBATS for complex patterns.  
✅ **Synthetic Data Generation** – Improves model robustness by adding noise to training data.  
✅ **Web-Based Interface** – Uses **Streamlit** for an interactive experience.  
✅ **Power BI Dashboard** – Visualizes trends and insights in an intuitive format.  

## **Why This Project?**  
Unlike IoT-based commercial solutions, this model provides **transparency** and can be **customized** as per specific energy requirements. It leverages **statistical models** and **synthetic data augmentation** to improve forecasting accuracy.  

## **Future Scope**  
🚀 Integrate **LSTM & Prophet** for advanced deep learning-based forecasting.  
🚀 Optimize models with **hyperparameter tuning & feature selection**.  
🚀 Extend dashboard functionality to include **real-time data streaming**.  

My contribution for this project was the core idea and some critical contributions before ML models like Data Preprocessing and Feature Engineering. In our project TBATS outperformed all other as it has the lowest RMSE compared to other ML models. Integration of Stream lit and Dashboard brings this project to real-world usage. 

## **Other Contributors**  
👤 **Vansh Sachdeva** – ML Model Development (ARIMA, SARIMA, TBATS)  
👤 **Marmik Parashar** – API Deployment & Web Interface  
👤 **Shashwat Mishra** – BI Dashboard


