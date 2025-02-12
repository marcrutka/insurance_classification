# Project: Classification Models Analysis for an Insurance Sales Campaign

## 📌 Project Overview
This project aims to analyze various classification models to identify the best-performing model for predicting customer responses to an **insurance company's sales campaign**. Based on available customer attributes, the models learn to classify whether a client will respond positively or negatively to the campaign.

## 📂 Project Structure
- `Projekt Zas BI(ENG).ipynb` – Main Jupyter Notebook containing the entire analysis and modeling workflow.
- `train.csv` – Dataset used for model training.
- `README.md` – This file, describing the project.

## 🔧 Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - `pandas`, `numpy` – Data manipulation
  - `matplotlib`, `seaborn` – Data visualization
  - `scikit-learn` – Machine learning models and evaluation metrics
  - `XGBoost` – Advanced classification model
  - `imblearn` – Data balancing techniques, including **SMOTE**

### **Available Features**
The dataset contains information on:
- **Demographics**: Gender, Age, Region Code Type.
- **Vehicles**: Vehicle Age, Previous Vehicle Damage History.
- **Policy Details**: Premium Amount, Sourcing Channel, etc.

The dataset is publicly available on Kaggle and can be accessed at the following link: [Health Insurance Cross Sell Prediction Dataset](https://www.kaggle.com/datasets/anmolkumar/health-insurance-cross-sell-prediction/data?select=sample_submission.csv&fbclid=IwY2xjawIZbOxleHRuA2FlbQIxMAABHZChmnT88E-h9FX5UiQvxJJRYbwJwD84BNvjJlqF6rc9ev0D1SLAGPJBvg_aem_uM2bQdMAugfNL7-DHle55w).

## 🔬 Analysis Workflow
1. **Data Loading and Cleaning** – Removing unnecessary columns and performing an initial exploration.
2. **Dimensionality Reduction** – Implementing **PCA (Principal Component Analysis)** to improve feature representation.
3. **Handling Imbalanced Data** – Applying **SMOTE (Synthetic Minority Over-sampling Technique)** to address class imbalance issues.
4. **Data Splitting** – Dividing the dataset into training and testing sets using `train_test_split`.
5. **Model Training**:
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - XGBoost
6. **Model Evaluation** – Using metrics such as accuracy, F1-score, recall, precision, and confusion matrix to assess performance.

## 📊 Results & Key Takeaways
- Several classification models were tested and compared.
- Model performance was evaluated based on multiple metrics.
- **XGBoost** achieved the best overall results in terms of accuracy and generalization.
- The implementation of **PCA** and **SMOTE** improved classification performance by reducing noise in data and balancing class distributions.

## 🚀 How to Run the Project
1. **Install the required libraries:**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost imbalanced-learn
   ```
2. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
3. **Open and run `Projekt Zas BI(ENG).ipynb`.**

## 📌 Author
This project was developed to explore various classification techniques in the context of **marketing analysis for an insurance company**.

---
**📢 If you find this project valuable, don't forget to leave a ⭐ on GitHub!** 🚀

