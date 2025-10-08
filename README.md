# 🪔 Diwali Sales Analysis Project – Python | Jupyter Notebook

---

## 📘 Project Overview
This project focuses on analyzing **Diwali sales data** to understand customer purchasing behavior and sales trends using **Python**.  
The analysis was performed in **Jupyter Notebook** using **NumPy, Pandas, Matplotlib, and Seaborn** libraries.

---

## 🧩 Steps Followed

### **1. Importing Libraries**
- Imported essential Python libraries:
  - `NumPy`
  - `Pandas`
  - `Matplotlib`
  - `Seaborn`

### **2. Importing the Dataset**
- Imported the CSV file into the Jupyter environment using `pd.read_csv()`.
- Displayed the first few records using:
  - `df.shape` – to check total rows and columns  
  - `df.head()` – to preview dataset  
  - `df.info()` – to view column datatypes and null values  

### **3. Data Cleaning & Transformation**
- Dropped unrelated and blank columns using `drop()`.  
- Checked for missing values using `isnull().sum()`.  
- Dropped null values using `dropna(inplace=True)`.  
- Changed the data type of the `Amount` column from **float** to **integer** using `astype(int)`.  
- Renamed columns for clarity.  

### **4. Data Description**
- Used `describe()` to generate summary statistics for the dataset.  
- Focused on specific columns (like *Age, Orders, and Amount*) to observe data distribution.

---

## 📊 Exploratory Data Analysis (EDA)

### **1. Gender Analysis**
- Plotted a **bar chart** for **Gender** and its **count**.  
- Created a **bar chart** for **Gender vs Total Amount** comparison.  
- **Insight:**  
  From the above graph, most of the buyers are **female**, and their **purchasing power is higher than male** customers.

### **2. Age Analysis**
- Created a **bar chart** for **Age Group vs Total Count**.  
- Created another chart for **Total Amount vs Age Group**.  
- **Insight:**  
  Majority of buyers belong to the **26–35 age group**.

### **3. State-wise Analysis**
- Plotted a **bar chart** showing the **total number of orders from top 10 states**.  
- Plotted another bar chart showing the **total amount/sales from top 10 states**.  
- **Top States:** Uttar Pradesh, Maharashtra, and Karnataka.

### **4. Occupation Analysis**
- Created a **bar chart** for **Occupation vs Total Amount**.  
- **Insight:**  
  Buyers are mostly from **IT**, **Healthcare**, and **Aviation** sectors.

### **5. Product Category Analysis**
- Plotted a **bar chart** for **Product Category vs Amount Sold**.  
- **Top Categories:** Food, Clothing, and Electronics.

---

## 🧠 Conclusion
From the analysis, we can conclude that:

- **Married women** aged **26–35 years**  Belonging to **Uttar Pradesh, Maharashtra, and Karnataka**  Working in **IT, Healthcare, and Aviation sectors** Are more likely to purchase products from **Food, Clothing, and Electronics** categories.  

---

## 🛠️ Tools & Libraries Used
- **Python**
- **Jupyter Notebook**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**

---

✨ This project demonstrates the use of **Python for data cleaning, visualization, and analysis**, showcasing how customer and sales data can be turned into actionable business insights.
