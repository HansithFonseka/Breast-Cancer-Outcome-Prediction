
# 🎗️ Breast Cancer Outcome Prediction

Welcome to the **Breast Cancer Outcome Prediction** project! 🚀  
This machine learning project predicts breast cancer patient outcomes using classification and regression models.  
The goal is to predict **mortality status (Alive/Dead)** and **survival months**, achieving **85.3% classification accuracy** and an **80-month survival prediction**. 🩺

---

## 📖 Project Overview

This project tackles two case studies using a breast cancer dataset:

### Case Study A: Classification 📊
Predicts whether a patient is Alive or Dead based on features like **Age**, **T_Stage**, and **Tumor_Size**.  
**Models used:** Logistic Regression, Naive Bayes, KNN, and a Voting Classifier ensemble.

### Case Study B: Regression 📈
Predicts **Survival Months** using Decision Tree Regressors, with a focus on **interpretability and generalization**.

🧾 The project includes **three Jupyter notebooks** for data preprocessing, modeling, and evaluation, along with a **detailed report** summarizing the findings.

---

## 🛠️ Technologies Used

- Python 🐍  
- scikit-learn *(Logistic Regression, KNN, Naive Bayes, Decision Trees, Voting Classifier)*  
- pandas & NumPy *(data manipulation)*  
- Matplotlib & Seaborn *(visualization)* 📉  
- SMOTE *(handling class imbalance)*  
- GridSearchCV *(hyperparameter tuning)*  
- Jupyter Notebooks *(development environment)* 📓

---

## 🌟 Key Achievements

- **High Classification Accuracy:** Achieved **85.3% accuracy** with Logistic Regression for predicting mortality status, with **0.63 recall for the minority class (Dead)** using SMOTE. ✅  
- **Survival Prediction:** Predicted **80 months survival** for a new patient using a Decision Tree Regressor (*max_depth=4*), with a **Mean Absolute Error (MAE)** of **19.05 months**. ⏳  
- **Robust Preprocessing:** Handled missing values, outliers (using IQR), and categorical encoding. 🧹  

---

## 📂 Repository Structure

```
Breast-Cancer-Outcome-Prediction/
├── notebooks/
│   ├── Final_Python_Notebook_1.ipynb    # Data preprocessing 🧼
│   ├── Final_Python_Notebook_2.ipynb    # Classification with SMOTE 📊
│   ├── Final_Python_Notebook_3.ipynb    # Ensemble & regression 📈
├── requirements.txt                     # Python dependencies 📋
├── README.md                            # You're here! 👋
```

> ⚠️ **Note**: The dataset is not included due to academic/privacy restrictions.  
> You can use similar datasets (e.g., from [SEER](https://seer.cancer.gov/survivaltime)) to replicate the results.

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/Breast-Cancer-Outcome-Prediction.git
cd Breast-Cancer-Outcome-Prediction
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Prepare the Data

- Obtain a breast cancer dataset with features like:  
  `Age`, `Sex`, `T_Stage`, `Tumor_Size`, `Mortality_Status`, `Survival_Months`
- Place the dataset in a **`data/`** folder and update file paths in the notebooks.

### 4️⃣ Run the Notebooks

```bash
jupyter notebook
```

> Start with `Final_Python_Notebook_1.ipynb` for preprocessing, then proceed to `Notebook_2` and `Notebook_3`.

---

## 📊 Results & Insights

### 🔹 Case Study A: Classification

- **Best Model:** Logistic Regression (Notebook 2)  
  - Accuracy: **85.3%**  
  - Precision: **0.59**  
  - Recall (Dead): **0.63** (using SMOTE)
- **Ensemble:** Voting Classifier (Notebook 3)  
  - Accuracy: **84%**  
  - Improved **AUC**
- **Challenge:** Class imbalance (~85% Alive, ~15% Dead)  
  - Addressed using **SMOTE**

### 🔹 Case Study B: Regression

- **Best Model:** Decision Tree Regressor (*max_depth=4*, Notebook 3)  
  - MAE: **19.05**  
  - R² Score: **-0.10**
- **Prediction:** **80 months** survival for patient **B002565**  
- **Insight:** Tree’s limited depth prevented overfitting but caused underfitting (R² < 0).

---

## 🔧 Future Improvements

- 🧪 **Advanced Models:** Try Random Forest or XGBoost  
- ⚖️ **Class Imbalance:** Apply SMOTE consistently  
- 📉 **Regression Fit:** Tune Decision Tree depth or try ensemble regressors  
- 🧑‍🔬 **Feature Engineering:** Drop noisy features like Occupation  

---

## 📚 References

- Kuhn, M., & Johnson, K. (2013). *Applied Predictive Modeling*. Springer.  
- SEER Cancer Data: [https://seer.cancer.gov/survivaltime](https://seer.cancer.gov/survivaltime)

---

## 📄 License

This project is licensed under the **MIT License** – feel free to use and modify it! 🌟

---

## 🙋 Connect with Me

📧 **Email:** hansithlochana@gmail.com  
🔗 **LinkedIn:** [linkedin.com/in/hansith-fonseka](https://www.linkedin.com/in/hansith-fonseka)  
🐙 **GitHub:** [github.com/HansithFonseka](https://github.com/HansithFonseka)
