# 💳 Customer Credit Risk Data Pipeline

<p align="center">
  <b>End-to-End Data Preprocessing & Feature Engineering for Credit Risk Modeling</b><br>
  <i>From raw multi-source data to a machine learning-ready dataset</i>
</p>

---

## 🚀 About the Project

In real-world financial systems, data is rarely clean, complete, or structured.  
This project focuses on building a **robust preprocessing pipeline** that transforms raw customer data into a reliable dataset for **credit risk prediction**.

The goal is not just cleaning data, but **understanding, structuring, and enhancing it** so that machine learning models can make accurate and meaningful predictions.

---

## 🧠 Problem Context

Financial institutions rely on customer data to assess **creditworthiness**.  
However, raw datasets often suffer from:

- Missing values  
- Inconsistent formats  
- Outliers and noise  
- Mixed data types  
- Lack of meaningful features  

This project addresses these challenges through a **systematic data preparation workflow**.

---

## 🔗 Data Integration

The dataset was constructed by combining multiple sources:

- **Transactional data (CSV)** → customer financial activity  
- **Metadata (JSON)** → customer-level attributes  
- **Relational data (SQL)** → repayment history  
- **External indicators (API)** → economic context  

These were merged into a **single unified dataset**, ensuring consistency across all records.

---

## 🔍 Data Understanding

Before any transformation, the dataset was explored to understand:

- Data types and structure  
- Distribution of numerical variables  
- Category balance in categorical variables  
- Missing value patterns  
- Potential anomalies  

This step guided all subsequent preprocessing decisions.

---

## 🧹 Data Cleaning Strategy

### Handling Missing Values

Different strategies were applied depending on the nature of the feature:

- **Statistical imputation** for numerical stability  
- **Most frequent replacement** for categorical consistency  
- **Random sampling** to preserve distribution  
- **Missing indicators** to retain information about missingness  
- **KNN and MICE** for capturing relationships between variables  

Rather than relying on a single method, multiple approaches were used to ensure **data integrity and realism**.

---

### Treating Outliers

Outliers were handled carefully to avoid losing valuable information:

- Extreme values were **identified using statistical methods**  
- Some were **removed when clearly invalid**  
- Others were **capped or adjusted** to reduce their influence  

This ensured a balance between **data accuracy and dataset size retention**.

---

## 🧠 Feature Engineering

Raw data rarely contains all the information needed for prediction.  
New features were created to capture deeper insights:

- **Debt-to-Income Ratio** → financial burden indicator  
- **Spending-to-Income Ratio** → spending behavior  
- **Average Monthly Transactions** → activity level  

These features provide **contextual meaning**, not just raw values.

---

## 🔄 Data Transformation

To make the data more suitable for modeling:

- Skewed variables were transformed using **log, square root, and power transformations**  
- Distributions were normalized using **Box-Cox and Yeo-Johnson techniques**  

This improves how models interpret relationships within the data.

---

## 🔢 Encoding & Representation

Categorical data was converted into numerical form using:

- **Ordinal encoding** for ordered categories  
- **One-hot encoding** for nominal variables  
- **Label encoding** for binary features  

This ensures compatibility with machine learning algorithms while preserving meaning.

---

## 📊 Feature Scaling

Different scaling techniques were applied to ensure:

- Features contribute equally to models  
- Large values do not dominate smaller ones  
- Algorithms converge faster and perform better  

Scaling methods were chosen based on **data distribution and robustness needs**.

---

## 📦 Final Dataset

After all transformations, the dataset is:

- ✔ Clean and consistent  
- ✔ Free from missing values  
- ✔ Robust to outliers  
- ✔ Properly encoded and scaled  
- ✔ Enriched with meaningful features  

📁 **Output:** `final_credit_risk_dataset.csv`

---

## 🎯 Why This Matters

A machine learning model is only as good as the data it is trained on.

This project demonstrates that:

- Proper preprocessing significantly improves model performance  
- Feature engineering adds real predictive power  
- Data understanding is as important as modeling  

---

## 🛠️ Tools & Technologies

- Python  
- Pandas & NumPy  
- Scikit-learn  
- SciPy  

---

## ✨ Key Takeaways

- Data preprocessing is not just cleaning — it's **data transformation with purpose**  
- Combining multiple techniques leads to better results  
- Feature engineering bridges the gap between raw data and intelligent models  

---

## 🚀 Next Steps

This dataset can now be used for:

- Credit risk classification models  
- Customer segmentation  
- Financial behavior analysis  

---

<p align="center">
  💡 <b>Good models start with great data.</b>
</p>
