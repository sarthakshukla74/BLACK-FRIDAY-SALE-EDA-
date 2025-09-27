# 🛍️ Black Friday Sales Data Analysis

This project analyzes the **Black Friday Sales Dataset** using Python (Pandas, NumPy, Matplotlib, and Seaborn).  
It provides insights into **customer demographics, purchase behavior, product popularity, and spending patterns**.

---

## 📂 Dataset
- File: `BlackFriday.csv`
- Rows: ~550,000+
- Columns:
  - `User_ID` → Unique identifier for customers
  - `Product_ID` → Unique identifier for products
  - `Gender` → M / F
  - `Age` → Customer age groups
  - `Occupation` → Occupation code
  - `City_Category` → A / B / C
  - `Stay_In_Current_City_Years` → Number of years in current city
  - `Marital_Status` → 0 = Single, 1 = Married
  - `Product_Category_1` → Main product category
  - `Purchase` → Purchase amount

---

## ⚙️ Tech Stack
- **Language**: Python 3  
- **Libraries**:
  - `pandas` → Data manipulation
  - `numpy` → Numerical analysis
  - `matplotlib` → Data visualization
  - `seaborn` → Advanced plots

---

## 📊 Analysis Performed

### 1. **Data Cleaning**
- Removed `Product_Category_2` and `Product_Category_3` due to missing values.
- Checked for nulls and datatypes.
- Verified number of unique users, products, genders, occupations, and marital statuses.

### 2. **Univariate Analysis**
- **Gender distribution** (Pie & Bar plot)  
- **Purchase behavior by Gender** (Total & Average spend)  
- **Age distribution** and purchase amounts  
- **Marital status** analysis  

### 3. **Bivariate & Multivariate Analysis**
- **Gender vs Age groups**  
- **Gender vs Marital status**  
- **City Category vs Age / Occupation / Gender**  
- **Stay in city vs Purchases**  
- **Occupation vs Purchases**  

### 4. **Product Analysis**
- Distribution of **Product Categories**  
- **Top 10 Products** by:
  - Total purchase amount
  - Average purchase value  

### 5. **Derived Features**
- Created **MaritalGender** = Gender + Marital Status combination  
- Compared purchases by **Age, Gender, Marital Status, and City**  

---

## 📈 Visualizations
Some key plots generated:
- Pie chart of **Gender ratio**  
- Bar chart of **Purchase distribution by Age**  
- Average purchase across **City Categories**  
- Count plots for **Occupation, Marital Status, Stay Years**  
- Top product categories purchased  

---

## 🔑 Key Insights
- Male customers dominate purchases compared to female customers.  
- Customers in the **26–35 age group** spend the most.  
- **City Category B** has the highest purchase contribution.  
- Married vs single differences in spending are noticeable, with **single men spending more**.  
- Certain product categories (like electronics & fashion) dominate total sales.  

---

## 🚀 How to Run
1. Upload the dataset to **Google Colab**:
   ```python
   from google.colab import files
   uploaded = files.upload()
