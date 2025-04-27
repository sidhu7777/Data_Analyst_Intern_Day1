# Data_Analyst_Intern_Day1



# Student Performance Indicator (ML Project)

This project explores the impact of various socio-demographic factors on student academic performance.  
It covers the full Machine Learning project life cycle from data collection to model evaluation, using structured methodologies and best practices.

---

##  Project Workflow

- **Understanding the Problem Statement**  
  Analyze how factors like gender, ethnicity, parental education, lunch types, and test preparation impact student test scores.

- **Data Collection**  
  Acquired relevant student performance datasets containing demographic details and scores in Math, Reading, and Writing.

- **Data Validation and Checks**  
  Verified data types, missing values, duplications, and performed basic sanity checks.

- **Exploratory Data Analysis (EDA)**  
  Visualized feature distributions, correlations, and patterns influencing student performance.

- **Data Pre-Processing**  
  - Encoding categorical variables
  - Scaling features
  - Splitting data into training and testing sets

- **Model Training**  
  Applied regression models (e.g., Linear Regression) to predict student scores based on features.

- **Model Selection**  
  Compared multiple models based on R² score and selected the best-performing algorithm.

---

##  Key Insights

- Test scores across subjects (Math, Reading, Writing) are strongly positively correlated.
- Student performance is significantly influenced by:
  - **Lunch type** (students with standard lunch outperform those with free/reduced lunch)
  - **Ethnicity** and **parental level of education**
- **Females** lead both in pass percentages and top scores compared to males.
- Completing a **test preparation course** shows some benefit but does not drastically impact overall scores.

---

##  Technologies Used

- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-Learn**

---

##  Project Structure

```
Student_Performance_Indicator/
│
├── notebooks/               # Jupyter notebooks (EDA, modeling)
├── README.md                # Project documentation
└── requirements.txt         # Required Python packages
```

---

##  Future Work

- Explore classification models to predict pass/fail labels.
- Incorporate external socio-economic datasets for richer analysis.
- Build a simple Flask or Streamlit app for score prediction.

---



