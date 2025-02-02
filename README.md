# StudySleep-Performance-Predictor
This project was made in First year of University by myself and it predicts and visualizes student performance based on study and sleep hours, using a linear model to explore their relationship.

# 🎓 StudySleep Performance Predictor

## 📌 Overview  
This project predicts and visualizes **student performance** based on **study hours** and **sleeping hours** using a **linear regression model**. The goal is to explore the relationship between these two factors and their impact on student performance, and to generate visual insights through scatter plots.

---

## 🧑‍💻 Objective  
The objective of this project is to model student performance by combining the hours spent studying and sleeping, and to predict performance using a linear equation. The visualization helps in understanding how the sum of these factors affects student performance.

---

## 🛠️ Features & Methods  

### ✅ **1. Performance Prediction Model**  
- A linear regression model is used to predict student performance based on two input features: study hours and sleeping hours.  
- The model predicts performance with the equation: \( \text{Performance} = 8 \times \text{(study + sleep)} + 50 \).

### ✅ **2. Data Visualization**  
- Scatter plots visualize the relationship between **student record** (sum of study and sleep hours) and **predicted performance**.
- The impact of study and sleep hours on performance is shown using color-coded scatter plots.

---

## 📊 Visualizations  

### 🔥 **Performance vs. Student Record**  
Visualize the predicted performance based on combined student record (study + sleep hours). The plot shows how different combinations of these factors impact performance.

### 🎯 **Optimization & Learning History**  
Track the performance progression based on different study and sleep hours using plots, showcasing the optimal predictions and visualizing the learning process.

---

## 🛠️ Installation & Usage  

### **🔹 Prerequisites**  
Ensure you have **Python 3+** installed along with the following libraries:  
```sh
pip install numpy pandas matplotlib seaborn
