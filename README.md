# Credit Card Fraud Detection Using Machine Learning  

Welcome to our **Credit Card Fraud Detection** project repository! This project focuses on building reliable and accurate machine learning models to identify fraudulent credit card transactions, addressing a critical issue in the financial sector.  

## 🌟 **Overview**  

The dataset used for this project contains transactions made by European cardholders in September 2013. Out of 284,807 transactions, only 492 are fraudulent, highlighting the extreme class imbalance (fraud makes up 0.172%).  
We used **Logistic Regression** and **Random Forest** classifiers to develop a robust detection system, tackling the class imbalance with advanced preprocessing techniques and evaluation methods.  

---

## 🛠 **Features**  

- **Data Balancing**:  
  Implemented **undersampling** to create a balanced subset with equal fraudulent and non-fraudulent transactions for unbiased training.  

- **Streamlined Workflow**:  
  Leveraged **scikit-learn Pipelines** for an efficient and reproducible process, integrating preprocessing, training, and evaluation.  

- **Hyperparameter Tuning**:  
  Used **GridSearchCV** to optimize model hyperparameters, ensuring the best possible performance.  

- **Evaluation with AUPRC**:  
  Evaluated model performance using the **Area Under the Precision-Recall Curve (AUPRC)**, ideal for imbalanced datasets.  

---

## 📊 **Model Performance**  

- **Logistic Regression**:  
  - **Training AUPRC**: [Insert Training AUPRC]  
  - **Testing AUPRC**: [Insert Testing AUPRC]  

- **Random Forest Classifier**:  
  - **Training AUPRC**: [Insert Training AUPRC]  
  - **Testing AUPRC**: [Insert Testing AUPRC]  

---

## 📁 **Project Structure**  

- `data/`: Dataset files (not included, refer to [Kaggle Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)).  
- `notebooks/`: Jupyter notebooks with detailed analysis and model training.  
- `src/`: Python scripts for preprocessing, feature engineering, and modeling.  
- `results/`: Model performance metrics and evaluation results.  

---

## 🚀 **How to Use**  

1. Clone this repository:  
   ```bash  
   git clone https://github.com/yourusername/credit-card-fraud-detection.git  
