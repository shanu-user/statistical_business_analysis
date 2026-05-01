
# 📊 Statistical Business Analysis on Sales Data

## 🔷 Overview
This project performs a comprehensive statistical analysis on sales data to identify key drivers of revenue and provide actionable business insights. The analysis focuses on understanding the impact of **Quantity, Price, and Product categories** on **Total Sales** using statistical techniques.

---

## 🎯 Objective
- Analyze sales data using statistical methods  
- Identify relationships between variables  
- Perform hypothesis testing  
- Build regression models for prediction  
- Generate business insights  

---

## 📁 Dataset Description
The dataset contains 100 records with the following features:

- Date  
- Product  
- Quantity  
- Price  
- Customer_ID  
- Region  
- Total_Sales  

✔ No missing values  
✔ Clean and structured dataset  

---

## 🛠️ Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- SciPy (Hypothesis Testing)  
- Statsmodels (Regression Analysis)  
- ReportLab (PDF generation)  

---

## 📊 Analysis Performed

### 1. Descriptive Statistics
- Calculated mean, median, mode  
- Analyzed variance and standard deviation  

📌 Insight:
Sales data shows high variability and right-skewed distribution.

---

### 2. Distribution Analysis
- Histogram plots for Total Sales and Price  
- Boxplot for Product vs Sales  

📌 Insight:
Presence of high-value transactions influencing overall revenue.

---

### 3. Correlation Analysis
- Pearson correlation between:
  - Quantity and Total Sales  
  - Price and Total Sales  

📌 Results:
- Quantity vs Sales: **r = 0.688 (Strong)**  
- Price vs Sales: **r = 0.646 (Moderate-Strong)**  

📌 Insight:
Both Quantity and Price significantly impact Total Sales.

---

### 4. Hypothesis Testing

#### ✔ Correlation Tests
- Both relationships are statistically significant (p < 0.05)

#### ✔ ANOVA (Product vs Sales)
- p-value = 0.093  

📌 Insight:
No significant difference in sales across products.

---

### 5. Confidence Interval
- Mean Total Sales: **123,650**  
- 95% CI: **(103,776 , 143,524)**  

📌 Insight:
Sales estimates are reliable but show variability.

---

### 6. Regression Analysis
- Model: Total_Sales ~ Quantity + Price  

📊 Results:
- R² = **0.884**  
- Both variables are statistically significant  

📌 Insight:
- Quantity is the strongest driver of sales  
- Price also contributes positively  

---

## 📈 Key Business Insights

- 📌 Quantity is the most influential factor for revenue growth  
- 📌 Price has a significant positive impact on sales  
- 📌 Product category does not significantly affect sales  
- 📌 High-value transactions contribute heavily to revenue  

---

## 📄 Project Structure
