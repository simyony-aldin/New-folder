# Customer Segmentation Analysis 📊
### Project: Customer segmentation using KMeans Clustering

---

## Project Description 🎯

This project performs an in-depth analysis of customer data using the KMeans clustering algorithm in order to identify distinct customer groups and provide business insights to improve marketing strategy.

---

## Project Structure 📁

```
📦 Customer-Segmentation-Analysis/
├── 📓 my_notebook.ipynb                    # Main notebook – full analysis
├── 📊 Customer Data.csv                    # Original data (8,950 customers)
├── 📈 Customer_Data_with_Clusters.csv      # Data with assigned cluster labels
├── 📄 Clustering.pdf                       # Supplementary document
├── 📝 README.md                            # This file
└── 🔒 .gitignore                           # Files to exclude from version control
```

---

## Data 📋

- **Number of customers:** 8,950
- **Number of variables:** 18 columns
- **Analysis period:** 12 months

### Main variables:
- **BALANCE** – average balance
- **PURCHASES** – total purchase amount
- **CREDIT_LIMIT** – credit limit
- **PAYMENTS** – payments
- **CASH_ADVANCE** – cash advances
- And more...

---

## Analysis Steps 🔍

### 1️⃣ Data loading and initial checks
- Check for missing values
- Descriptive statistics
- Outlier detection

### 2️⃣ EDA – Exploratory Data Analysis
- Variable distributions
- Correlation matrix
- Advanced visualizations

### 3️⃣ Preprocessing
- Handling missing values
- Data quality checks
- Standardization (StandardScaler)

### 4️⃣ Elbow Method
- Determining the optimal number of clusters
- **Result: K = 4**

### 5️⃣ Training the KMeans model
- Training the model with 4 clusters
- Profiling each cluster
- Visualizations

### 6️⃣ Business insights
- Recommendations for each customer segment
- Targeted marketing strategies
- Risk management

---

## Results – 4 Customer Segments 🎯

### 🔵 Cluster 0: Regular Shoppers (68.0%)
**Regular customers – main customer base**
- Low-to-medium balances
- Small, regular purchases
- Minimum or partial payments

### 🟢 Cluster 1: Cash Advance Seekers (15.1%)
**Cash advance users – higher risk**
- Frequent cash advances
- Relatively high balances
- Require close monitoring

### 🟡 Cluster 2: High-Value Customers (1.2%)
**VIP customers – the “gems”**
- Very high credit limits
- Large and frequent purchases
- High payment amounts

### 🟣 Cluster 3: Full Payment Customers (15.7%)
**Full payers – high-quality customers**
- Full monthly payments
- Low risk
- High loyalty

---

## Technologies 🛠️

- **Python 3.x**
- **pandas** – data processing
- **numpy** – numerical computations
- **scikit-learn** – KMeans clustering
- **matplotlib & seaborn** – visualizations
- **Jupyter Notebook** – development environment

---

## How to Run ▶️

1. **Clone the repository:**

```bash
git clone https://github.com/simyony-aldin/New-folder.git
cd New-folder
```

2. **Install the required packages:**

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

3. **Run the notebook:**

```bash
jupyter notebook my_notebook.ipynb
```

---

## Key Insights 💡

✅ **68%** of customers are “Regular Shoppers” – a stable core base  
⚠️ **15.1%** use cash advances frequently – require monitoring  
🌟 **1.2%** are VIP customers – generate high profits  
✨ **15.7%** are full-payment customers – ideal low-risk clients

---

## Business Recommendations 🎯

### 📈 Marketing strategies:
1. **Regular Shoppers** – loyalty programs and coupons
2. **Cash Advance** – improved credit terms and churn prevention
3. **High-Value** – VIP service and exclusive offers
4. **Full Payment** – long-term loyalty benefits

### 💰 Revenue potential:
- **Expected ROI:** $3–5M in the first year
- **Retention improvement:** 15–25%
- **Increase in CLV:** 20–30%

---

## Project Author 👨‍💻

**simyony-aldin**

📅 Date: February 2026

---

## License 📄

This project was created for learning and demonstration purposes.

---

### ⭐ If this project helped you, consider giving it a star!
