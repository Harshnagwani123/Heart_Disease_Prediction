# Heart_Disease_Prediction

# 🫀 Heart Disease Prediction

This project predicts the likelihood of **heart disease** using various **machine learning models**.  
It is based on the [Heart Disease UCI Dataset](https://www.kaggle.com/ronitf/heart-disease-uci).

---

## 📌 Project Workflow
1. **Data Loading** – Import dataset using Pandas.  
2. **Exploratory Data Analysis (EDA)** – Visualize data with Seaborn & Matplotlib.  
3. **Data Preprocessing**  
   - Handling missing values  
   - Feature scaling (StandardScaler)  
   - Encoding categorical variables  
4. **Model Training**  
   - Logistic Regression  
   - Decision Tree  
   - Random Forest  
   - Support Vector Machine (SVM)  
5. **Model Evaluation**  
   - Accuracy Score  
   - Classification Report  
   - Confusion Matrix  
6. **Model Comparison** – Compare accuracy of all models.  

---

## 📊 Dataset Information
The dataset contains health records of patients with 14 attributes:

- **age**: Age of the patient  
- **sex**: Gender (1 = male, 0 = female)  
- **cp**: Chest pain type  
- **trestbps**: Resting blood pressure  
- **chol**: Serum cholesterol (mg/dl)  
- **fbs**: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)  
- **restecg**: Resting ECG results  
- **thalach**: Maximum heart rate achieved  
- **exang**: Exercise induced angina (1 = yes; 0 = no)  
- **oldpeak**: ST depression induced by exercise  
- **slope**: Slope of peak exercise ST segment  
- **ca**: Number of major vessels colored by fluoroscopy  
- **thal**: Thalassemia (blood disorder)  
- **target**: 1 = Heart disease present, 0 = No heart disease  

---

## ⚙️ Installation

Clone the repository:
```bash
git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction
