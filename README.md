# 🎓 International Education Cost Analysis

This project analyzes the costs associated with studying internationally, including tuition, rent, visa fees, and insurance costs. It uses a real-world dataset (`International_Education_Costs.csv`) and includes data exploration, statistical analysis, and visualizations.

---

## 📁 Dataset

**File**: `International_Education_Costs.csv`

**Columns Include**:
- `Country`, `City`, `University`, `Program`, `Level`
- `Duration_Years`: Program duration
- `Tuition_USD`: Tuition cost in USD
- `Rent_USD`: Average monthly rent
- `Visa_Fee_USD`, `Insurance_USD`: Additional expenses
- `Living_Cost_Index`, `Exchange_Rate`

---

## 🧪 Tasks Completed

### ✅ Task 1: Load and Explore the Dataset
- Loaded dataset using pandas
- Inspected data types and missing values
- Cleaned the data by dropping rows with missing values

### ✅ Task 2: Basic Data Analysis
- Computed descriptive statistics (mean, std, min, max)
- Grouped by `Country` to analyze:
  - Mean tuition
  - Tuition range (min, max, mean, std)
  - Insurance costs and duration of study
  - Total cost (Tuition + Rent)
- Calculated correlation between numerical variables

### ✅ Task 3: Data Visualization (with Seaborn & Matplotlib)
- 📈 **Line Chart**: Avg. Tuition by Country (Top 10)
- 📊 **Bar Chart**: Avg. Rent by Country (Top 10)
- 📉 **Histogram**: Tuition distribution
- 🔘 **Scatter Plot**: Tuition vs Rent

All plots include titles, axes labels, and improved Seaborn styling for clarity.

---

## 🛠️ How to Run

### Option 1: Python Script
1. Download `education_cost_analysis_seaborn.py`
2. Ensure `International_Education_Costs.csv` is in the same folder
3. Run the script with:
```bash
python education_cost_analysis_seaborn.py
