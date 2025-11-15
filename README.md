---

# **Hiring Decision & Salary Prediction Using Machine Learning**

This project analyzes recruitment data to build predictive models for **hiring decisions** and **salary estimation**. Traditional hiring processes often rely on subjective judgment, which can lead to inconsistencies and biases. This project applies a **data-driven, supervised machine learning approach** to support fair, consistent, and efficient hiring.

The project includes exploratory data analysis (EDA), data preprocessing, model development, evaluation, and results visualization.

---

## **📌 Project Overview**

This project has two main objectives:

### **1. Predict Hiring Decisions**

Determine whether a candidate is likely to be hired based on features such as:

* Age
* Gender
* Experience
* Skills Score
* Interview Score
* Personality Score
* Education Level
* Recruitment Strategy
* Previous Companies

### **2. Predict Salary for Selected Candidates**

For candidates predicted to be hired, a regression model is built to estimate expected salary using:

* Experience
* Education
* Skill Score
* Interview Score
* Personality Score
* Other relevant numerical/categorical attributes

These predictions help:

* **Organizations** improve recruitment strategies
* **Candidates** understand salary expectations and hiring factors

---

## **📁 Repository Structure**

```
├── FinalProject_2322478.ipynb            # Main notebook containing complete analysis and models
├── recruitment_data.csv                  # Dataset for hiring decision prediction
├── Salary Data.csv                       # Dataset for salary prediction
├── finalproject-2322478.pdf              # Final written report
├── Presentation_ppt.pptx                 # Presentation slides
├── Presentation.mp4                      # Recorded presentation video
├── Images/                               # Images/plots used in the project
├── Images_2322478.zip                    # Zipped images
├── Presentation_2322478.zip              # Zipped presentation files
└── README.md                             # Project documentation
```

---

## **🔍 Key Steps in the Project**

### **1. Data Cleaning & Transformation**

* Handled missing values
* Encoded categorical variables (Gender, Education Level, Recruitment Strategy)
* Normalized numerical columns
* Split datasets into **train/test**

### **2. Exploratory Data Analysis (EDA)**

* Distribution of age, experience, skill, interview, and personality scores
* Gender and education-level distribution
* Hiring decision patterns across recruitment strategies
* Correlation heatmaps
* Outlier detection using boxplots

### **3. Model Development**

#### **Hiring Decision (Classification)**

Tested models:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

#### **Salary Prediction (Regression)**

Models used:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

**Linear Regression performed best**, achieving ~90% accuracy (MAPE-based).

---

## **📊 Model Evaluation Metrics**

* **Accuracy**
* **Mean Absolute Error (MAE)**
* **Mean Absolute Percentage Error (MAPE)**
* **Confusion Matrix (for hiring prediction)**

---

## **✨ Results Summary**

### **Hiring Decision**

The best-performing model effectively predicts whether a candidate will be hired based on their profile.
Key influential features:

* Interview Score
* Skill Score
* Experience
* Education Level

### **Salary Prediction**

Linear Regression outperformed tree-based models due to a largely **linear relationship** between experience, skills, education, and salary.

Accuracy achieved: **~90%**

---

## **📦 Requirements**

Install required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

---

## **▶️ How to Run the Project**

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-github-username>/<repo-name>.git
   ```
2. Open the Jupyter Notebook:

   ```bash
   jupyter notebook FinalProject_2322478.ipynb
   ```
3. Run cells step-by-step to reproduce:

   * Data preprocessing
   * EDA visualizations
   * Model building
   * Evaluation and results

---

## **💡 Future Improvements**

* Add hyperparameter tuning (GridSearchCV / RandomizedSearchCV)
* Deploy the model using Flask or Streamlit
* Build an interactive candidate evaluation dashboard
* Incorporate resume text analysis using NLP

---

## **👨‍💻 Author**

**Kunal — Aspiring Data Scientist**
Master’s Student in Applied Data Science
Focused on ML, analytics, and data-driven decision-making.

---
