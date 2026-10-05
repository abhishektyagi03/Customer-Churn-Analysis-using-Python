# 📊 Customer Churn Analysis using Python

This project performs **Customer Churn Analysis using Python** to understand customer behavior and identify patterns associated with customer churn.

The analysis uses **Exploratory Data Analysis (EDA)** techniques with Pandas, NumPy, Matplotlib, and Seaborn.

## 🎯 Project Objective

The main objective of this project is to analyze customer data and understand:

- Customer churn distribution
- Customer distribution by country
- Churn rate by country
- Customer distribution by gender
- Churn rate by gender
- Basic data quality and dataset characteristics

## 📂 Dataset

The dataset contains **10,000 customer records and 14 columns**.

Important columns include:

- `CustomerId`
- `Surname`
- `CreditScore`
- `Geography`
- `Gender`
- `Age`
- `Tenure`
- `Balance`
- `NumOfProducts`
- `HasCrCard`
- `IsActiveMember`
- `EstimatedSalary`
- `Exited`

The `Exited` column represents customer churn:

- `0` → Customer stayed
- `1` → Customer exited

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔍 Analysis Performed

### 1. Data Exploration

The project checks:

- Dataset shape
- Column names
- Data types
- Descriptive information
- Missing values
- Duplicate records
- Unique values

### 2. Customer Churn Distribution

A count plot is used to visualize the number of customers who stayed and exited.

### 3. Geography Analysis

Customer distribution is analyzed across:

- France
- Germany
- Spain

The churn rate for each country is calculated and visualized using a bar chart.

### 4. Gender Analysis

The project analyzes customer distribution by gender and calculates the churn rate for male and female customers.

## 📈 Key Analysis Results

The notebook contains analysis showing:

- **10,000 customers** across **14 columns**
- Customers are distributed across France, Germany, and Spain.
- Churn rates are compared between different countries.
- Gender-wise churn rates are calculated.
- The notebook's analysis shows a higher churn percentage for **female customers** than male customers in this dataset.

## 📊 Visualizations

The project includes visualizations such as:

- Customer Churn Distribution
- Customers by Geography
- Customer Churn Rate by Country
- Gender-wise churn analysis

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/your-username/customer-churn-analysis.git
```

### 2. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Open Jupyter Notebook

```bash
jupyter notebook
```

### 4. Open the notebook

Open:

```text
Customer Churn Analysis python 6.ipynb
```

### 5. Update the dataset path

The notebook currently uses a local Windows file path. Update it according to your dataset location:

```python
df = pd.read_csv("Churn_Modelling.csv")
```

## 📁 Project Structure

```text
Customer-Churn-Analysis/
│
├── Customer Churn Analysis python 6.ipynb
├── Churn_Modelling.csv
└── README.md
```

## 💡 Skills Demonstrated

This project demonstrates practical skills in:

- Data Cleaning
- Exploratory Data Analysis
- Data Aggregation
- GroupBy Analysis
- Data Visualization
- Customer Churn Analysis
- Python for Data Analytics

## 👨‍💻 Author

**Abhishek Tyagi**

MCA | Aspiring Data Analyst / Data Scientist

---

⭐ If you find this project useful, consider giving the repository a star!
