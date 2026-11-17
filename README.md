# Electric Vehicle (EV) Adoption Analysis

## 📌 Project Overview

This project focuses on analyzing an Electric Vehicle (EV) Adoption dataset to understand the factors influencing consumers' decisions to purchase electric vehicles.

The analysis explores customer demographics, income, commuting distance, charging infrastructure, environmental concerns, government subsidies, and range anxiety to identify patterns related to EV purchase intentions.

## 📂 Dataset Information

- **Dataset:** EV Adoption and Range Anxiety Dataset
- **Records:** 10,000
- **Features:** 15
- **Target Variable:** `Will_Buy_EV`

### Key Features
- Customer demographics (Age, Gender, City Type)
- Annual Income
- Daily Commuting Distance
- Current Car Type and Number of Cars Owned
- Charging Stations Availability
- Home Charging Possibility
- Environmental Concern Level
- Government Subsidy Availability
- Range Anxiety Level
- EV Purchase Intention

## 🛠️ Technologies Used

- **Python** – Programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **Jupyter Notebook** – Development environment

## 🔍 Analysis Workflow

1. **Data Loading & Exploration**
   - Loading the dataset
   - Understanding data structure and dimensions
   - Statistical summary and unique value analysis

2. **Data Cleaning**
   - Identifying missing values
   - Handling missing numerical values using median imputation
   - Verifying data consistency

3. **Feature Engineering**
   - Creating an `Age_Group` column based on customer age.

4. **Exploratory Data Analysis (EDA)**
   - Univariate Analysis
   - Bivariate Analysis
   - Distribution Analysis
   - Correlation Analysis
   - Outlier Detection

5. **Data Visualization**
   - Analyzing relationships between customer characteristics and EV purchase intentions.
   - Visualizing charging infrastructure, environmental concerns, and range anxiety.
   - Comparing income and commuting patterns across purchase-intention groups.

## 🎯 Project Objective

To explore the major factors associated with electric vehicle adoption and understand how customer characteristics, charging accessibility, environmental awareness, and range anxiety relate to EV purchase intentions.

## 📁 Project Structure

```text
Electric-Vehicle-Adoption/
│
├── EV_Adoption_Analysis_Completed.ipynb
├── EV_Adoption_and_Range_Anxiety_Dataset.csv
└── README.md
```

## ▶️ How to Run the Project

1. Clone this repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project folder:

   ```bash
   cd Electric-Vehicle-Adoption
   ```

3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

4. Open the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `EV_Adoption_Analysis_Completed.ipynb` and run the cells.

## 📊 Conclusion

This project provides an exploratory understanding of EV adoption patterns by examining demographic, economic, environmental, and infrastructure-related factors. It helps identify relationships between these factors and consumers' EV purchase intentions through data analysis and visualization.

---

**Project Category:** Data Analytics | Exploratory Data Analysis (EDA)
