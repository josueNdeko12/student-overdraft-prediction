# Student Overdraft Prediction

This project was developed for the **CSCI 3900 - Data Science and Machine Learning** course. It aims to predict whether a student has ever overdrawn a checking account using features such as **Age**, **Gender**, and **DaysDrink** (alcohol consumption frequency).

The dataset consists of 450 student records and includes both categorical and numerical features. Several classification models were trained and evaluated to determine the most effective predictor.

## 📁 Dataset

The dataset `Project_Data.csv` contains the following columns:
- `Gender` (categorical)
- `Age` (numerical)
- `DaysDrink` (numerical)
- `Overdrawn` (target label)

## ⚙️ Preprocessing Steps

- Removed rows with missing values.
- Replaced inconsistent gender labels (`M` → `Male`, `F` → `Female`).
- Encoded the `Gender` column using one-hot encoding.
- Detected and handled outliers in the `DaysDrink` column.
- Split the dataset into 70% training and 30% testing.
- Final features used: `Gender_Male`, `Gender_Female`, `Age`, `DaysDrink`

## 🧠 Models Trained

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

Each model was evaluated using:
- **Accuracy**
- **Confusion Matrix**

## 📊 Evaluation Results

| Model              | Accuracy |
|-------------------|----------|
| Logistic Regression | 78.95%   |
| K-Nearest Neighbors | 78.95%   |
| Decision Tree       | 64.91%   |
| Random Forest       | 56.14%   |
| Support Vector Machine (SVM) | **85.96%** |

The **Support Vector Machine** (SVM) model outperformed all others and was selected as the best model for this classification task.

## 📂 Files

- `Project_Data.csv` — Original dataset
- `student_overdraft_prediction.ipynb` — Main Jupyter notebook with full workflow
- `README.md` — Project documentation

## ✅ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/student-overdraft-prediction.git

   
# 💫 About Me:
SDE intern @ Amazon | AI Research @ PNNL & UAH | Dell Scholar | CDEP & Honors CS @ FVSU


# 💻 Tech Stack:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)

### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->

