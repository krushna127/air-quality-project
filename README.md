## 📅 Daily Progress Log (Air Quality Prediction Project)

I am keeping track of my learning day by day while working on this project.  
This shows how I improve step by step.

### 🗓️ Day 1
## 📅 Today’s Progress

Today I worked on my **Air Quality Prediction project** as a beginner learning data science.  

- Successfully loaded the dataset in Python using Pandas  
- Fixed column issues so all headers are recognized  
- Cleaned the data: dropped empty columns, filled missing values, and created a `DateTime` column  
- Performed basic Exploratory Data Analysis (EDA): histogram of CO levels and correlation heatmap  
- Built my first machine learning model (Linear Regression) to predict CO(GT) using T, RH, AH  
- Printed R² Score and Mean Squared Error (MSE)  
- Prepared a beginner-friendly README.md and started a daily log to track learning progress

## 📚 Resources & References

### Dataset
- [UCI Air Quality Dataset on Kaggle](https://www.kaggle.com/datasets/dakshbhalala/uci-air-quality-dataset)

This marks the **first version** of my project, ready to push to GitHub.

### 🗓️ Day 2
- Built my **first machine learning model (Linear Regression)**  
- Trained it to predict CO(GT) values using Temperature (T), Relative Humidity (RH), and Absolute Humidity (AH)  
- Evaluated the model using R² Score and Mean Squared Error (MSE)  
- Created a visualization: **Actual vs Predicted CO(GT)** scatter plot  
- Learned how to compare predictions with real-world values  

### 📅 Day 3 - Data Cleaning Fix

- Faced a **KeyError: 'Date'** while cleaning data.  
- Found the issue: I used `sep=";"` but the dataset is comma-separated.  
- Fixed by using `sep=","` in `read_csv` and stripping column names.  
- Now `Date` and `Time` load correctly.  
- Key learning: always check column names after reading a CSV.


---

👉 This log will keep growing as I update my project.
