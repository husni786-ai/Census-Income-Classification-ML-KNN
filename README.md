# 💰 Binary Classification Model for Income Prediction

This project contains a comprehensive Jupyter Notebook that implements a supervised machine learning solution for **Binary Classification**. The goal is to predict an individual's income bracket (typically $ >50\text{K}$ or $\le 50\text{K}$) based on various demographic and employment features, commonly using the Adult Census Income dataset.

---

## 🎯 Project Goals

The objective is to establish a robust and effective machine learning pipeline, demonstrating proficiency in data preprocessing and model evaluation for a standard classification task.

1.  **Data Preparation:** Load and inspect the structured census data.
2.  **Feature Engineering:** Apply essential preprocessing techniques, specifically **One-Hot Encoding**, to handle categorical features.
3.  **Model Training:** Train a suitable Scikit-learn classification algorithm on the prepared data. 
4.  **Evaluation:** Calculate and report key performance metrics, including **Accuracy Score**, to assess model generalization.

## 🗃️ Dataset Used

The model is designed for the **Adult Census Income Dataset**, which contains features such as age, education, marital status, occupation, and capital metrics, with the target variable being income level ($\le 50\text{K}$ or $>50\text{K}$).

## ⚙️ Technology Stack and Dependencies

The project is built on the standard Python data science stack, emphasizing Scikit-learn for its comprehensive ML capabilities.

| Library | Role |
| :--- | :--- |
| **`pandas` & `numpy`** | Data loading, manipulation, and numerical operations. |
| **`scikit-learn`** | Core ML framework for model selection, data splitting, and performance evaluation (`accuracy_score`). |
| **`sklearn.preprocessing`** | Crucial for handling categorical variables using **`OneHotEncoder`**. |
| **`plotly`** | Used for interactive data visualization and analysis (implied). |

### Installation
```bash
pip install pandas numpy scikit-learn plotly

```bash
pip install pandas numpy scikit-learn plotly
