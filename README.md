# Medicaid Enrollment Trend Analysis – VIII Group

## Project Overview
This project analyzes the **Medicaid VIII Group (New Adult Group)** enrollment trends across the United States, focusing on operational insights and process improvement opportunities. The analysis aims to support managers in Medicaid/CHIP programs by identifying trends, bottlenecks, and demographic patterns, providing actionable recommendations for enhancing efficiency.

The dataset includes state-wise enrollment counts, total enrollees, newly eligible members, and not newly eligible members.

---

## Tech Stack
- **Programming Languages:** Python, SQL
- **Libraries & Tools:** Pandas, Matplotlib, Seaborn, NumPy
- **Optional:** Power BI / Excel (for interactive dashboards)

---

## Features
1. Clean and preprocess Medicaid enrollment datasets.
2. Trend analysis of VIII Group enrollment over time.
3. State-level enrollment analysis to identify high-volume and delayed states.
4. Newly eligible vs. not newly eligible analysis.
5. Visualizations for operational insights:
   - Line charts for trends
   - Bar charts for top states
   - Percentage comparison of eligibility
6. Recommendations for process improvement and operational optimization.

---

## Dataset
- The dataset contains the following columns:
  - `State`: U.S. state or territory
  - `Total Medicaid Enrollees`: Total enrollees in Medicaid
  - `Total VIII Group Enrollees`: Enrollees in the New Adult Group
  - `Total VIII Group Newly Eligible Enrollees`
  - `Total VIII Group Not Newly Eligible Enrollees`
  - `Updated Year`, `Updated Month`, `Enrollment Year`, `Enrollment Month`, `Notes`

- **Source:** CMS Medicaid Enrollment Data (VIII Group)  
  [Download CSV](https://www.medicaid.gov/medicaid/national-medicaid-chip-program-information/medicaid-chip-enrollment-data/medicaid-enrollment-data-collected-through-mbes)

---

## Step-by-Step Implementation
1. **Data Loading & Cleaning**
   - Remove duplicates
   - Convert numeric columns
   - Generate a datetime column for enrollment month/year

2. **Analysis**
   - Calculate total enrollees and VIII Group percentages
   - Identify top states by enrollment
   - Evaluate newly eligible vs not newly eligible ratios
   - Detect trends and operational bottlenecks

3. **Visualization**
   - Line charts for monthly enrollment trends
   - Bar charts for state comparisons
   - Heatmaps for eligibility ratios

4. **Insights & Recommendations**
   - Identify states needing process improvements
   - Highlight enrollment trends for operational planning
   - Provide actionable insights for Medicaid/CHIP program managers

---

## How to Run
1. Clone the repository:
```bash
git clone https://github.com/yourusername/medicaid-enrollment-trend-analysis.git
