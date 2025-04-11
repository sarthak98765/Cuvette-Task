# 📊 Data Science TA Hiring Assignment – Cuvette

## 🎯 Objective

The goal of this assignment is to demonstrate proficiency in core data science concepts, data manipulation, and communication skills. It includes tasks in Python, SQL, Tableau, Excel, and AI tools.

---

## ✅ Section 1: Python + Machine Learning (Student Performance)

**Dataset:** Student Performance (Math & Portuguese)

### 🔧 Steps Performed:

- **Data Cleaning:**  
  - Merged `student-mat.csv` and `student-por.csv`.
  - Removed missing/null values and duplicates.
  - Encoded categorical variables using Label Encoding and One-Hot Encoding.

- **EDA (Exploratory Data Analysis):**
  - Visualized correlations using heatmaps.
  - Plotted distribution of final grades and failure rates by gender and parental education.

- **Modeling:**
  - Defined target variable as **Pass/Fail** based on final grade (`G3 >= 10`).
  - Used **Random Forest** and **Logistic Regression** for classification.
  - Split the dataset into train/test using `train_test_split`.

- **Evaluation Metrics:**
  - Accuracy Score
  - Confusion Matrix
  - F1 Score

> 📌 Code is well-commented with markdown cells for easy understanding.

---

## ✅ Section 2: SQL (Chinook Database)

**Tool Used:** SQLite Online

### 🔍 SQL Tasks Completed:

1. **Top 5 Customers** by total purchase amount.
2. **Most Popular Genre** by total tracks sold.
3. **Managers and Subordinates** using self-join on the employees table.
4. **Most Sold Album per Artist** using subqueries.
5. **Monthly Sales Trends** for 2013 using date functions and `GROUP BY`.

📁 All queries and screenshots of results are included in the `.sql` file and screenshots folder.

---

## ✅ Section 3: Tableau Dashboard (Airbnb NYC)

**Tool Used:** Tableau Public  
🔗 **[Dashboard Link](https://public.tableau.com/authoring/Cuvettetask/Dashboard1#1)**

### 📊 Dashboard Includes:

- Count of Listings by Neighborhood
- Price Distribution by Room Type
- Availability Trend Visualization
- Interactive Filters:
  - Room Type
  - Neighborhood

> Published and publicly accessible on Tableau Public.

---

## ✅ Section 4: Excel (Online Retail Dataset)

**Dataset:** Online Retail Dataset (UCI)

### 📋 Tasks Completed:

- **Data Cleaning:**
  - Removed null rows and duplicate entries using `Data > Remove Duplicates`.

- **Pivot Table:**
  - Total Sales grouped by **Country** and **Month** (InvoiceDate grouped by Month & Year).

- **Formulas Applied:**
  - **Average Order Value** = `Total Sales / Number of Orders`
  - **% Contribution of Country** = `(Country Sales / Total Sales) * 100`

- **Conditional Formatting:**
  - Highlighted **Top 5 Countries** by revenue.

- **Chart:**
  - Created a **Line Chart** to visualize **Monthly Revenue Trend**.

---

## ✅ Section 5: Bonus Response

### 💡 Supporting Struggling Students:

> I believe in empathetic guidance. If students are struggling with concepts or deadlines, I’d organize doubt-clearing sessions, share extra learning resources, and provide flexible timelines when feasible. Encouragement and small wins go a long way in boosting motivation.

### 🧠 Explaining "Gradient Descent" Simply:

> Imagine you're blindfolded on a hill and trying to reach the bottom by feeling which direction goes downhill. Each step is based on how steep the slope is. That’s gradient descent — it adjusts parameters step-by-step to minimize errors, just like walking downhill.

---

## 🏁 Conclusion

This assignment provided a comprehensive hands-on experience across different areas of data science—from Python modeling and SQL analytics to data visualization using Tableau and Excel. It also tested adaptability with AI tools, which are becoming increasingly important in the field.

By completing all sections, I demonstrated the ability to not just solve problems but communicate insights clearly—something crucial for a Teaching Assistant role. I enjoyed every step of this task and look forward to supporting and mentoring students as they navigate their data science journey.
