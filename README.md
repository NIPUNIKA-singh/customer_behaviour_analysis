# customer_behaviour_analysis
Analyzed customer shopping behavior data to identify purchasing patterns, customer preferences, and sales trends. Performed data cleaning, exploratory data analysis, and business insights using Python, SQL, and visualization tools. Studied customer demographics, product performance, and buying behavior to support data-driven decisions.
# 📊 Data Analytics Project

## 📌 Overview

This project demonstrates an end-to-end **Data Analytics workflow**, starting from raw dataset ingestion to generating actionable business insights. The project includes data loading, exploratory data analysis (EDA), data cleaning, SQL-based analysis, interactive dashboard development, and final reporting.

The objective is to transform raw data into meaningful insights using Python, SQL, and Power BI while following industry-standard analytics practices.

---

## 📂 Dataset

The dataset used in this project contains structured information related to customer/business operations.

### Dataset Details:
- **Source:** Public dataset / Kaggle / Business-provided dataset
- **Format:** CSV
- **Records:** XXXXX
- **Features:** XX columns

### Key Data Attributes:
- Numerical variables
- Categorical variables
- Date/time fields
- Business-related metrics

---

## 🛠️ Tools & Technologies Used

### Programming & Analysis
- **Python**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn

### Database & SQL
- PostgreSQL / MySQL / SQL Server
- SQL queries for:
  - Data exploration
  - Aggregations
  - Filtering
  - Joins
  - Business insights

### Visualization & Reporting
- Power BI
- Gamma (AI-powered presentation creation)
- Microsoft PowerPoint

### Development Environment
- Jupyter Notebook
- VS Code
- Git & GitHub

---

# 🔄 Project Workflow

## 1. Data Loading

- Imported the dataset into Python using Pandas.
- Checked dataset structure, dimensions, and data types.
- Performed initial data inspection.

```python
import pandas as pd

df = pd.read_csv("dataset.csv")
df.head()
```

---

## 2. Exploratory Data Analysis (EDA)

Performed detailed analysis to understand patterns and relationships within the data.

### EDA Activities:
- Dataset overview
- Statistical summary
- Missing value analysis
- Duplicate detection
- Distribution analysis
- Outlier identification
- Correlation analysis
- Data visualization

Libraries used:
- Matplotlib
- Seaborn

---

## 3. Data Cleaning & Preprocessing

The dataset was cleaned to improve data quality and prepare it for analysis.

### Cleaning Steps:
- Handled missing values
- Removed duplicate records
- Corrected inconsistent values
- Converted data types
- Standardized categorical values
- Treated outliers where required

The cleaned dataset was exported for database analysis.

---

## 4. SQL Analysis

Loaded the cleaned dataset into a relational database and performed SQL analysis.

### Database Used:
- PostgreSQL / MySQL / SQL Server

### SQL Operations Performed:
- Data extraction
- Aggregation using GROUP BY
- Filtering using WHERE and HAVING
- Joins between tables
- Subqueries
- Window functions
- Business KPI calculations

Example:

```sql
SELECT 
    category,
    COUNT(*) AS total_orders,
    SUM(sales) AS total_sales
FROM customer_data
GROUP BY category;
```

---

## 5. Power BI Dashboard Development

Built an interactive dashboard to visualize important insights and KPIs.

### Dashboard Features:
- KPI cards
- Interactive filters and slicers
- Trend analysis
- Category-wise performance
- Customer insights
- Data-driven visualizations

### Dashboard Preview:

<img width="1366" height="768" alt="Screenshot (353)" src="https://github.com/user-attachments/assets/c3804bd1-d124-4776-8738-2ff25b2fb39f" />


---

# 📈 Key Results & Insights

The analysis helped identify important business patterns and trends.

### Major Findings:
- Identified key performance indicators affecting business outcomes.
- Analyzed customer/product/category performance.
- Discovered trends through visual and statistical analysis.
- Generated actionable insights for decision-making.

---

# 📑 Report & Presentation

Created a professional project report covering:

- Business problem statement
- Data understanding
- Data cleaning process
- Analysis methodology
- SQL insights
- Dashboard findings
- Final recommendations

A presentation was created using **Gamma** to summarize project outcomes and communicate insights effectively.

---

# 🚀 How to Run the Project

Follow these steps to reproduce the analysis:

### 1. Clone Repository

```bash
git clone https://github.com/NIPUNIKA-singh/project-name.git
```

### 2. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### 3. Run Python Notebook

Open:

```
Data_Analysis_Project.ipynb
```

Run all cells to perform:
- Data loading
- EDA
- Data cleaning
- Visualization

### 4. Database Setup

- Create a database in PostgreSQL/MySQL/SQL Server.
- Import the cleaned dataset.
- Execute SQL scripts available in the `SQL` folder.

### 5. Power BI Dashboard

Open:

```
PowerBI_Dashboard.pbix
```

Refresh the data connection to view interactive dashboards.

---

# 📁 Project Structure

```
Data-Analytics-Project/
│
├── Dataset/
│   └── dataset.csv
│
├── Python/
│   └── Data_Analysis_Project.ipynb
│
├── SQL/
│   └── analysis_queries.sql
│
├── Dashboard/
│   └── PowerBI_Dashboard.pbix
│
├── Report/
│   └── Project_Report.pdf
│
├── Presentation/
│   └── Project_Presentation.pptx
│
└── README.md
```

---

# 👤 Author

**NIPUNIKA SINGH**

- LinkedIn: https://www.linkedin.com/in/nipunika-singh-405843323/
- GitHub: https://github.com/NIPUNIKA-singh

---

⭐ If you found this project useful, consider giving it a star!
