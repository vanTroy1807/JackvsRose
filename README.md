# 🚢 JackvsRose
### Titanic Survival Prediction using Machine Learning

An end-to-end machine learning project built using the Kaggle Titanic dataset.

The objective of this project is to predict whether a passenger survived the Titanic disaster using demographic and travel-related information. Rather than focusing solely on leaderboard performance, this project was built to understand the complete machine learning workflow—from data exploration to model evaluation and hyperparameter tuning.

---

## 📖 Project Overview

This notebook covers the complete machine learning pipeline:

- Loading and understanding the dataset
- Exploratory Data Analysis (EDA)
- Data cleaning
- Feature engineering
- Encoding categorical variables
- Training multiple machine learning models
- Hyperparameter tuning
- Model evaluation
- Kaggle submission generation

---

## 📂 Repository Structure

```
JackvsRose/
│
├── titanic_survival_pred.ipynb     # Complete notebook
├── submission.csv                  # Kaggle submission
├── requirements.txt                # Project dependencies
└── README.md
```

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Exploratory Data Analysis

Some of the questions explored during EDA include:

- How does passenger class affect survival?
- Does gender influence survival?
- Does age influence survival?
- Does fare correlate with survival?
- Which embarkation port had the highest survival rate?
- How do family size and travelling alone affect survival?

These observations guided the feature engineering process.

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

- Handling missing values
- Dropping irrelevant features
- Feature engineering
- One-hot encoding of categorical variables
- Train-validation split

---

## 🧠 Feature Engineering

The following features were created to improve model performance:

| Feature | Description |
|----------|-------------|
| **famsize** | Total family members travelling together |
| **isalone** | Whether the passenger was travelling alone |
| **fareperperson** | Fare divided by family size |
| **title** | Passenger title extracted from the Name column |

---

## 🤖 Models Trained

The following models were implemented and compared:

- Decision Tree Classifier
- Tuned Decision Tree
- Random Forest Classifier
- Tuned Random Forest

Hyperparameter tuning was performed manually to understand its effect on model performance.

---

## 📈 Results

| Model | Validation Accuracy |
|-------|--------------------:|
| Decision Tree | ~77% |
| Tuned Decision Tree | ~85% |
| Random Forest | ~84–85% |
| **Tuned Random Forest** | **~86%** |

The tuned Random Forest achieved the best validation accuracy.

---

## 💡 Key Learnings

Through this project I learned:

- Performing effective Exploratory Data Analysis
- Handling missing data
- Feature engineering
- One-hot encoding
- Train-validation splitting
- Decision Trees
- Random Forests
- Hyperparameter tuning
- Evaluating and comparing machine learning models

---

## 🚀 Running the Project

Clone the repository

```bash
git clone git@github.com:vanTroy1807/JackvsRose.git
```

Move into the project directory

```bash
cd JackvsRose
```

Create and activate a virtual environment

```bash
python -m venv .venv
source .venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter

```bash
jupyter lab
```

---

## 📌 Dataset

This project uses the **Titanic - Machine Learning from Disaster** competition dataset on Kaggle.

The dataset is not included in this repository.

Download it here:

https://www.kaggle.com/competitions/titanic

---

## 🔮 Future Improvements

- Cross Validation
- GridSearchCV
- RandomizedSearchCV
- Gradient Boosting
- Additional feature engineering

---

## 🙌 Acknowledgements

- Kaggle Learn
- Kaggle Titanic Competition
- Scikit-learn Documentation

---

## 📬 Contact

**Ojaswi Shrivastava**

- GitHub: https://github.com/vanTroy1807
- LinkedIn: https://www.linkedin.com/in/ojaswi-shrivastava-162162333/
