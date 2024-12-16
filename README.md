# 🚴‍♂️ Bike Sharing Demand Prediction  

## 📄 Project Overview  
This project demonstrates the use of machine learning techniques to predict bike-sharing demand in Seoul. By analyzing historical and weather data, we identified trends and key factors influencing demand, ultimately building an accurate predictive model.  

The insights from this project can help optimize resource allocation, improve operational efficiency, and enhance customer satisfaction in bike-sharing systems.  

---

## 🔑 Key Features  
- Conducted **Exploratory Data Analysis (EDA)** to uncover trends in bike demand based on time, weather, and seasons.  
- Found patterns such as:  
  - **High demand** during morning and evening.  
  - **Highest demand** in June, and **low demand** in winter.  
- Discovered **multicollinearity** between temperature and dew point temperature.  
- Built and compared multiple machine learning models:  
  - **Linear Regression**  
  - **Decision Tree**  
  - **Random Forest**  
  - **Gradient Boosting**  
  - **Extreme Gradient Boosting (XGBoost)**  
- Achieved a **best accuracy of 97% (train)** and **92% (test)** using XGBoost.  
- Learned that removing outliers negatively impacts model performance.  

---

## 🛠️ Technologies Used  
- **Programming Language**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost  
- **Machine Learning Techniques**: Regression, Decision Trees, Random Forest, Gradient Boosting  
- **Tools**: Jupyter Notebook  

---

## 📊 Insights and Learnings  
- **High demand** occurs during peak hours (morning and evening).  
- **Seasonal patterns** affect demand, with June being the busiest month and winter having the least demand.  
- **Feature engineering** (e.g., extracting hour and season) significantly improved model performance.  
- Proper handling of **multicollinearity** and **outliers** is crucial for reliable predictions.  

---

## 🚀 How to Use  
1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/bike-sharing-demand-prediction.git
