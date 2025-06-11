# 🎓 Student Performance Prediction

This is a machine learning project to predict students' CGPA using a trained regression model. It allows data entry through a Streamlit interface and gives users performance predictions based on a variety of academic and personal input factors.
## ✅ Features

- Linear Regression and Random Forest model options
- User authentication (Sign up / Log in)
- Visual analytics (bar chart, pair plots, line/area plots)
- Prediction results with class category
- Error evaluation (MAE, MSE)
- Clean and interactive interface with Streamlit

---

## 🖼️ Screenshots

### 🔷 Home Page
A simple entry interface on Streamlit  
![Home](pro1.png)

---

### 🔐 Authentication  
Login and signup options  
![Login](pro2.png)  
![Signup](pro3.png)

---

### 📊 Dashboard with Dataset View  
Browse raw GPA and background data  
![Dashboard](pro4.png)

---

### 📉 Pairplots and Distributions  
Relationships between various features  
![Pairplots](pro5.png)

---

### 📝 Input Form for Prediction  
Users enter academic and personal data  
![Form 1](pro6.png)  
![Form 2](pro7.png)  
![Form 3](pro8.png)

---

### 📋 Output Prediction  
Final CGPA prediction with interpretation  
![Prediction Output](pr010.png)  
![Model Errors](pro9.png)

---

### 📈 Additional Visualizations  
Bar chart of CGPA distribution  
![Bar Chart](pro12.png)

Area chart showing multiple variable trends  
![Area Chart](pro11.png)

---

### 🧠 Core Logic & Model Code

#### Model Imports & Setup  
![Code 1](pro13.png)

#### Feature Dictionaries  
Used to map text input to numeric values  
![Code 2](pro14.png)

#### Prediction Input Section  
Streamlit form that captures prediction inputs  
![Code 3](pro15.png)

#### Random Forest Prediction Logic  
Model training, evaluation, and output  
![Code 4](pro16.png)

#### User Login System Using SQLite  
Authentication backend  
![Code 5](pro17.png)

---

## ⚙️ Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python (scikit-learn, pandas, SQLite)
- **Models**: Linear Regression, Random Forest Classifier
- **Visualization**: Matplotlib, Seaborn

---

## 🧪 Model Details

- **Inputs**: GPA from previous years, exam results, personal habits, access to resources, etc.
- **Output**: Predicted CGPA (out of 5.0)
- **Target Label Classes**:
  - First Class
  - Second Class Upper
  - Second Class Lower
  - Pass
  - Fail

---

### 📌 Conclusion
This was my first machine learning project. I improved it bit by bit. I plan to share more updates and refinements soon.

