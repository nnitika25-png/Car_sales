
# Car Sales Prediction and Business Insights 

> Developed an end-to-end data analytics project to identify the key factors that influence vehicle sales performance. The project combines data cleaning, exploratory data analysis (EDA), feature engineering, statistical modeling, and business analysis to uncover actionable insights that support data-driven decision-making in the automotive industry.

## 📊 Project Overview

### Business Problem

Automotive manufacturers invest significant resources in vehicle design, pricing, and product development. Understanding which vehicle characteristics drive sales performance is essential for making informed business decisions and improving market competitiveness.

### Project Objective

The primary objective of this project is to:

- Identify the vehicle characteristics that have the greatest impact on sales performance.
- Analyze pricing, vehicle specifications, and market trends.
- Build a regression model to evaluate the relationship between vehicle features and sales.
- Generate business insights and strategic recommendations based on the findings.

### Research Question

> Which vehicle characteristics have the greatest impact on sales performance, and how can these insights support business decision-making?

### Methodology

The project follows a structured data analytics workflow:

- Data Exploration
- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Correlation Analysis
- Feature Engineering
- Feature Selection
- Multiple Linear Regression
- Model Evaluation
- Business Insights and Recommendations

## ⚙️ Setup

### 1. Clone the Repository

Clone the project repository and navigate to the project directory:

```bash
git clone https://github.com/nnitika25-png/Car_sales.git
cd Car_sales
```

### 2. Create the Environment and Install Dependencies

This project uses **uv** for dependency management.

Install **uv** from [uv.dev](https://uv.dev) and synchronize the project dependencies:

```bash
uv sync
```
---

## 🛠️ Technologies and Libraries

### Programming and Environment

- **Python 3.13** – Core programming language
- **uv** – Fast Python package and environment manager
- **Jupyter Notebook** – Interactive development and analysis environment

### Data Processing

- **Pandas** – Data cleaning, manipulation, and analysis

### Data Visualization

- **Matplotlib** – Statistical and business visualizations
- **Seaborn** – Advanced data visualization and exploratory analysis

### Statistical Modeling

- **Statsmodels** – Multiple Linear Regression and statistical analysis

### Data Source

- **KaggleHub** – Dataset download and integration from Kaggle

---

## ▶️ Project Execution

Run the notebooks in the following order:

| Step | Notebook | Purpose |
|--------|----------|----------|
| 1 | `01_exploration.ipynb` | Initial data exploration and dataset understanding |
| 2 | `02_preprocessing.ipynb` | Data cleaning, preprocessing, and feature preparation |
| 3 | `03_Exploratory_Data_Analysis.ipynb` | Exploratory analysis, visualizations, and relationship analysis |
| 4 | `04_Modeling_and_Insights.ipynb` | Feature selection, regression modeling, and model evaluation |
| 5 | `05_Strategic_Recommendations.ipynb` | Business insights, segmentation analysis, and recommendations |

---

## 📌 Project Workflow

```text
Raw Data
    ↓
Data Exploration
    ↓
Data Cleaning & Preprocessing
    ↓
Exploratory Data Analysis
    ↓
Feature Selection
    ↓
Regression Modeling
    ↓
Model Evaluation
    ↓
Business Insights
    ↓
Strategic Recommendations
```

## 📂 Project Structure

```text
Car_sales/
│
├── data/
│   ├── raw/                    # Raw source data
│   └── processed/              # Cleaned and transformed datasets
│
├── docs/                       # Documentation and supporting materials
│
├── notebooks/
│   ├── 01_exploration.ipynb                    # Initial data exploration
│   ├── 02_preprocessing.ipynb                 # Data cleaning and preprocessing
│   ├── 03_Exploratory_Data_Analysis.ipynb     # EDA and visualization
│   ├── 04_Modeling_and_Insights.ipynb         # Feature selection and regression modeling
│   └── 05_Strategic_Recommendations.ipynb     # Business insights and recommendations
│
├── src/
│   └── core/
│       ├── __init__.py
│       └── data.py             # Data loading and utility functions
│
├── pyproject.toml              # Project dependencies and configuration
├── uv.lock                     # Locked dependency versions
├── .gitignore
├── .python-version
└── README.md
```
---

## 📈 Key Findings

The analysis revealed several important insights about vehicle sales performance:

- Vehicle price and wheelbase were identified as the strongest predictors of sales.
- Higher-priced vehicles generally achieve lower sales volumes.
- Vehicles with larger wheelbases tend to achieve higher sales volumes.
- Budget vehicles outperform premium vehicles in average sales performance.
- A small number of vehicle models contribute significantly to overall market sales.
- Ford dominates the market, with multiple models appearing among the top-selling vehicles.

## 💼 Business Recommendations

Based on the analysis, the following recommendations were identified:

### Pricing Strategy
Focus on competitively priced vehicles, as lower-priced vehicles consistently achieve higher sales volumes.

### Product Design
Consider offering larger vehicles, as larger wheelbase segments demonstrate stronger sales performance.

### Balance Price and Vehicle Features
Offer spacious vehicles at competitive price points to maximize both customer appeal and sales performance.

### Focus on High-Demand Product Segments
Identify and invest in vehicle segments with proven market demand while regularly reviewing underperforming products.

### Improve Future Sales Forecasting
Incorporate variables such as brand reputation, marketing activities, customer preferences, and economic conditions in future analyses to improve prediction accuracy.


## 🚀 Future Improvements

Potential enhancements to this project include:

- Testing advanced machine learning models such as Random Forest and XGBoost.
- Including external economic and market data.
- Building an interactive dashboard using Power BI.
---

## 👤 Author

**Nitika Abrol**

Aspiring Data Analyst with a background in Business Intelligence, Data Warehousing, SQL, Python, and Power BI.

GitHub: [nnitika25-png](https://github.com/nnitika25-png)
