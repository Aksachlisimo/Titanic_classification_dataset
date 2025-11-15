# 🚢 Titanic Classification

### 📘 Overview
A machine learning project that predicts the likelihood of survival on the Titanic using passenger data.  
The project follows a complete ML pipeline — from data preprocessing and exploratory analysis to model training, tuning, and evaluation.

## 🧠 Objectives
- Understand patterns in Titanic passenger data.  
- Train and evaluate classification models.  
- Identify key features influencing survival predictions.

## ⚙️ Tools & Libraries
- Python, Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

## 🚀 Workflow
- Data Loading & Cleaning  
- Exploratory Data Analysis (EDA)  
  - Checked feature distributions  
  - Visualized correlations between variables  
- Feature Engineering & Encoding  
- Model Training  
  - Logistic Regression  
  - Random Forest Classifier  
  - **SGDClassifier** (best performance)  
- Hyperparameter Tuning  
  - **RandomizedSearchCV** on **SGDClassifier**  
- Model Evaluation  
  - Accuracy, Precision, Recall, F1-score  

## 📊 Results
- **Best Model:** SGDClassifier (tuned)  
- **Accuracy Achieved:** *(insert your final score)*  
- **Key Influencing Features:** Sex, Pclass, Fare, Age  

## 📈 Visual Insights
- Females had significantly higher survival rates.  
- First-class passengers showed the highest survival probability.  
- Fare and age showed meaningful influence on survival.  

## 🧩 Key Takeaways
- Completed a full end-to-end ML classification workflow.  
- Improved skills in preprocessing, feature engineering, and model tuning.  
- Learned how model performance changes with different algorithms and hyperparameters.

## 📁 Notebook
- [View Project Notebook](./titanic_classification_dataset.ipynb)

## 🛠️ Setup Instructions
- Clone the repository: `git clone https://github.com/Aksachlisimo/titanic_classification_project.git`  
- Install dependencies: `pip install -r requirements.txt` *(include pandas, numpy, matplotlib, seaborn, scikit-learn)*  
- Open the notebook and run all cells to reproduce the results.

## 👨‍💻 Author
- **Mohamed Mouhimine**  
- **AI & Machine Learning Engineer**
