Here's an updated **README summary** with the results table included:  

---

# 🏥 Chronic Kidney Disease Prediction  
### **A Comparative Study on Machine Learning Models & Imputation Techniques**  

## 📌 Introduction  
Chronic Kidney Disease (CKD) is a progressive condition that affects kidney function and increases the risk of cardiovascular disease and end-stage kidney failure. This project aims to predict CKD using various **machine learning models**:  
- **Logistic Regression**  
- **Decision Tree**  
- **Random Forest**  
- **Linear Support Vector Machine (SVC)**  

The study also explores different **data imputation techniques** to handle missing values and improve model performance.  

## 📊 Dataset  
The dataset used in this study is the **Chronic Kidney Disease Dataset** from the **UCI Machine Learning Repository** (400 instances, 24 features). It includes key indicators such as blood pressure, glucose levels, and other medical parameters relevant to CKD diagnosis.  

🔗 **Source:** [UCI CKD Dataset](https://archive.ics.uci.edu/dataset/336/chronic+kidney+disease)  

## 🔄 Imputation Techniques  
To handle missing values, the following techniques were implemented:  
1. **KNN Imputation** – Uses nearest neighbors to estimate missing values.  
2. **Iterative Imputation** – Uses a Random Forest Regressor to iteratively predict missing values.  
3. **MICE Forest Imputation** – Uses Multiple Imputation by Chained Equations (MICE) to generate multiple imputed datasets and combine them.  

## 🤖 Machine Learning Models  
The following models were trained and evaluated:  
- **Logistic Regression**  
- **Decision Tree Classification**  
- **Random Forest Classification**  
- **Linear Support Vector Classification (SVC)**  

## 📈 Results  
The accuracy of each machine learning model with different imputation techniques is summarized in the table below:  

| **Imputation Technique** | **Logistic Regression** | **Decision Tree** | **Random Forest** | **Support Vector** |
|-------------------------|------------------|--------------|--------------|---------------|
| **KNN Imputation**        | 0.98             | 0.97         | 0.99         | 0.98          |
| **Iterative Imputation**  | 0.94             | 0.92         | 0.96         | 0.94          |
| **MICE Forest Imputation**| 0.95             | 0.97         | 0.96         | 0.95          |

![Screenshot 2025-02-06 234909](https://github.com/user-attachments/assets/77bc351d-749d-467f-8612-4dcfaaadadd3)

## 🚀 How to Run  
1️⃣ **Clone the repository**  
```bash
git clone https://github.com/yourusername/ckd-prediction.git
cd ckd-prediction
```  

2️⃣ **Install dependencies**  
```bash
pip install -r requirements.txt
```  

3️⃣ **Run the model**  
```bash
python main.py
```  

## 📜 License  
This project is open-source and licensed under the MIT License.  

---
