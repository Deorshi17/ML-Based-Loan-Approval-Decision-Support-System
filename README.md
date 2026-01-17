# CreditWise – Data-Driven Loan Approval Analytics
**Intelligent Loan Approval System (Data Analytics + Machine Learning)**




## 🔍 Overview

The **CreditWise Loan System** is an intelligent loan approval solution developed using **Data Analytics and Machine Learning** to support financial institutions in making **accurate, fast, and unbiased loan approval decisions.**

The system analyzes historical loan application data and predicts whether a loan should be **Approved (1)** or **Rejected (0)** before final human verification, helping banks reduce risk and improve operational efficiency.

## ❗ Problem Statement

A mid-sized financial company, **SecureTrust Bank**, offers personal and home loans to customers across **urban and rural regions of India.** Every day, **hundreds of customers apply for loans** through both online and branch-based applications.

Currently, SecureTrust Bank relies on a **manual verification process**, where loan officers evaluate applications by checking:

- Income proofs
- Employment details
- Credit history
- Supporting financial documents

This manual process is:

- Time-consuming
- Biased
- Inconsistent

As a result, the bank faces two major challenges:

**1.** **Good customers sometimes get rejected**, leading to loss of business

**2.** **High-risk customers sometimes get approved**, leading to financial losses

To address these issues, the bank plans to introduce an **intelligent loan approval system powered by Machine Learning** that can automatically analyze applicant details and **predict whether a loan should be Approved or Rejected**, before final human verification.

You are hired as a **Machine Learning Engineer** to design and develop this system using **historical loan application data**, enabling accurate, fast, and unbiased decision-making.

## 📂 Dataset

Each row in the dataset represents **one loan applicant,** and each column describes the applicant's **personal, financial, and credit-related attributes.**

### 🎯 Target Variable

**Loan_Approved**

- **1** → Approved
- **0** → Rejected

➡️ This makes the problem a **binary classification task (100%)**, where every prediction belongs to **one of two possible outcomes.**

### 📌 Feature Description

| Feature | Description |
|---------|-------------|
| Applicant_ID | Unique applicant identifier |
| Applicant_Income | Monthly income of applicant |
| Coapplicant_Income | Monthly income of co-applicant |
| Employment_Status | Salaried / Self-Employed / Business |
| Age | Applicant age |
| Marital_Status | Married / Single |
| Dependents | Number of dependents |
| Credit_Score | Credit bureau score |
| Existing_Loans | Number of running loans |
| DTI_Ratio | Debt-to-Income ratio |
| Savings | Savings balance |
| Collateral_Value | Value of collateral provided |
| Loan_Amount | Loan amount requested |
| Loan_Term | Loan duration (months) |
| Loan_Purpose | Home / Education / Personal / Business |
| Property_Area | Urban / Semi-Urban / Rural |
| Education_Level | Graduate / Postgraduate / Undergraduate |
| Gender | Male / Female |
| Employer_Category | Govt / Private / Self |

All features are used to help the model learn patterns from past loan decisions.

## 🛠 Tools and Technologies

- **Programming Language:** Python
- **Data Analysis Libraries:** Pandas, NumPy
- **Visualization Libraries:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Development Environment:** Jupyter Notebook

## ⚙️ Methods

The project follows a structured **Data Analytics + Machine Learning pipeline**:

**1.** **Data Understanding**
   - Identification of numerical and categorical features
   - Understanding the binary target variable (100%)

**2.** **Data Preprocessing**
   - Cleaning inconsistent or missing values
   - Encoding categorical variables
   - Preparing data for ML model training

**3.** **Feature Engineering**
- Encoding categorical variables into numerical formats suitable for machine learning models
- Structuring numerical features to ensure compatibility with supervised learning algorithms

**4.** **Exploratory Data Analysis (EDA)**
   - Distribution analysis of applicant income, loan amount, credit score, etc.
   - Comparative analysis between Approved vs Rejected applications
   - Identification of risk-related financial patterns

**5.** **Model Development**
- Implemented multiple supervised ML algorithms:
   - **K-Nearest Neighbors (KNN)**
   - **Logistic Regression**
   - **Naive Bayes**

**6.** **Prediction & Evaluation**
   - Performed **binary classification** for loan approval prediction
   - Evaluated models using:
      - **Precision**
      - **Recall**
      - **F1-Score**

## 📈 Key Insights

- Loan approval decisions depend on a **combination of financial stability, credit behavior, and loan burden,** not a single attribute.
- Credit-related features such as **credit score and DTI ratio** strongly influence approval patterns.
- The ML system ensures **100% consistency in decision logic,** unlike manual evaluation.
- Automated pre-verification reduces dependency on subjective human judgment.

## 📊 Dashboard / Output

- Visualizations created using **Matplotlib and Seaborn**:
  - Financial attribute distributions
  - Approved vs Rejected comparison plots

- Final Output:
  - **Binary loan approval prediction (100%)**
  - Clear Approved / Rejected decision for each applicant

These outputs help stakeholders understand both the prediction and the reasoning patterns behind it.

## ▶️ How to Run this Project?

**1.** Download or clone the project repository

**2.** Open `CWLS.ipynb` in Jupyter Notebook

**3.** Install required libraries:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

**4.** Run all notebook cells sequentially to:
- Load and preprocess data
- Perform EDA
- Apply feature engineering
- Train ML models
- Generate predictions and visual outputs

## ✅ Results & Conclusion

The **CreditWise Loan System** successfully demonstrates how **Machine Learning combined with Data Analytics** can improve traditional loan approval processes.

**Conclusion:**

- Enables **faster and unbiased decision-making**
- Reduces approval of high-risk applicants
- Prevents rejection of financially strong customers
- Acts as a decision-support system for human loan officers
- Provides a scalable foundation for real-world banking and financial analytics applications

This project reflects a **practical implementation of ML-driven risk assessment** aligned with real-world financial industry requirements.

## 📬 Contact

### **Deorshi Nishant**
*Data Analyst & Business Intelligence Professional*

---

### 🔗 Connect with me

<p align="left">
  <a href="https://www.linkedin.com/in/itsyournish/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:itsyournish07@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
</p>

---

*💼 Open to collaborations and new opportunities in Data Analytics & Business Intelligence*

*⭐ If you found this project helpful, please consider giving it a star!*
