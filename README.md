# ❤️ Heart Disease Prediction

This project predicts the likelihood of heart disease in patients using **Machine Learning models**. It takes patient health records such as age, cholesterol levels, blood pressure, and other clinical features, and predicts whether the person is at risk of developing heart disease.  

---

## 📌 Project Overview
- Built a **machine learning classification model** to detect heart disease.
- Used the **UCI Heart Disease dataset**.
- Explored data, cleaned it, and performed feature engineering.
- Trained and compared multiple ML algorithms (e.g., Logistic Regression, Random Forest, SVM, etc.).
- Evaluated the models using accuracy, precision, recall, and confusion matrix.

---

## 📊 Dataset
- **Name**: Heart Disease Dataset  
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/heart+Disease)  
- **Rows**: 303  
- **Columns**: 14  
- **Target**: `target` (1 = heart disease, 0 = no disease)

**Key Features:**
- `age`: Age of the patient  
- `sex`: Gender (1 = male, 0 = female)  
- `cp`: Chest pain type (4 types)  
- `trestbps`: Resting blood pressure  
- `chol`: Serum cholesterol (mg/dl)  
- `fbs`: Fasting blood sugar (>120 mg/dl, 1 = true; 0 = false)  
- `restecg`: Resting electrocardiographic results  
- `thalach`: Maximum heart rate achieved  
- `exang`: Exercise induced angina (1 = yes; 0 = no)  
- `oldpeak`: Depression induced by exercise relative to rest  
- `slope`: Slope of the peak exercise ST segment  
- `ca`: Number of major vessels (0–3) colored by fluoroscopy  
- `thal`: Thalassemia  
- `target`: Diagnosis of heart disease (1 = disease, 0 = no disease)  

---

## ⚙️ Technologies Used
- **Python 3**
- **Pandas, NumPy** (data handling)
- **Matplotlib, Seaborn** (visualization)
- **Scikit-learn** (ML models and evaluation)

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/bhargavatejagolla/heart-disease-prediction.git
   cd heart-disease-prediction
    ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook heartdieseasepredictions.ipynb
   ```
---
## 📈 Model Performance
- Compared algorithms like Logistic Regression, Random Forest, SVM, and KNN.  
- Achieved **~85% accuracy** (update this with your exact result).  
- Visualized feature importance and correlation among attributes.  

---

## 🔮 Future Improvements
- Deploy the model using **Flask/Streamlit** for an interactive web app.  
- Improve performance with **hyperparameter tuning**.  
- Test with larger and more diverse datasets.  

---

## 📂 Project Structure
```bash
   📁 heart-disease-prediction
 ┣ 📜 heartdieseasepredictions.ipynb   # Jupyter notebook with full code
 ┣ 📜 heart-disease.csv               # Dataset
 ┣ 📜 README.md                       # Project documentation
 ┗ 📜 requirements.txt                # Dependencies
 ```

---

##  Acknowledgments
- Dataset from [UCI Repository](https://archive.ics.uci.edu/ml/datasets/heart+Disease).  
- Inspiration from healthcare ML research.
  ---

## 👨‍💻 About Me

Hi, I’m **Bhargava Teja Golla** 👋  

- 🎓 Engineering student passionate about **Artificial Intelligence & Machine Learning**  
- 💡 Love working on **real-world ML projects** that make an impact  
- 🌱 Currently learning **Deep Learning & Full-Stack Development**  
- 🚀 Aspiring to build projects that combine **AI + Web Development**  
- 📫 Connect with me on  
  - [LinkedIn](https://www.linkedin.com/in/golla-bhargava-teja/)  
  - [GitHub](https://github.com/bhargavatejagolla)  

✨ *Thanks for visiting my project! Feedback and suggestions are always welcome.*  

