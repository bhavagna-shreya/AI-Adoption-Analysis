---

# 📈 Generative AI Industry Adoption Analysis (2023-2025)

---

## 📋 Project Overview

This project analyzes the rise of Generative AI adoption across industries from 2023 to 2024 and predicts industry-wise adoption rates for 2025.  

We perform:
- Deep Exploratory Data Analysis (EDA)
- Outlier Detection and Handling
- Feature Engineering
- Time Series Forecasting
- Multivariate Comparative Analysis
- KMeans Clustering (Unsupervised Machine Learning)

The project also includes **professional-grade visualizations** following best practices:  
minimalist design, no gridlines, clear annotations, clean layouts.

---

## 📚 Key Skills Demonstrated

- **Python for Data Analysis**: pandas, numpy
- **Statistical Profiling**: Skewness, Kurtosis, IQR
- **Visualization**: matplotlib, seaborn
- **Predictive Analytics**: Linear Regression for 2025 forecast
- **Clustering**: KMeans to group industries
- **Data Cleaning**: Outlier detection and capping
- **Feature Engineering**: Categorizing adoption rates
- **Business Storytelling**: Clean executive-level graphs and interpretation

---

## 🛠 Technologies Used

| Tool/Library | Purpose |
|:---|:---|
| Python | Programming Language |
| pandas | Data Manipulation |
| numpy | Numerical Computations |
| seaborn | Statistical Visualization |
| matplotlib | Plotting |
| scikit-learn | Machine Learning (KMeans, Linear Regression) |

---

## 📊 Project Workflow

### 1. Data Preparation
- 100-row synthetic dataset created simulating real-world adoption statistics.
- Fields include: Year, Country, Industry, Adoption Rate (%), Use Case.

### 2. Exploratory Data Analysis (EDA)
- Descriptive statistics
- Histogram + KDE plots
- Skewness and Kurtosis Calculation
- Outlier Detection (IQR Method)
- Boxplots

### 3. Feature Engineering
- Created a new **Adoption Category** feature:
  - High: ≥ 70%
  - Medium: 40% to 70%
  - Low: < 40%

### 4. Forecasting Adoption for 2025
- Linear Regression trained on 2023 and 2024 average adoption rates.
- Forecasted 2025 adoption rates for overall trend and per industry.

### 5. Comparative Industry Analysis
- Multivariate bar plots comparing 2023 vs 2024 adoption rates per industry.
- Identified industries with highest expected growth.

### 6. Clustering Analysis
- KMeans clustering based on **Adoption Rate (%)** and **Year**.
- Discovered natural groups of industries with similar AI adoption behaviors.

---

## 📈 Key Graphs

| Visualization | Description |
|:---|:---|
| Histogram + KDE | Distribution of Adoption Rates |
| Forecast Line Plot | Adoption rate trend prediction to 2025 |
| Multivariate Barplot | Industry-wise comparison of 2023 vs 2024 |
| Clean Boxplot | Outlier detection |
| KMeans Cluster Plot | Grouping industries based on behavior |

_All graphs designed cleanly: no gridlines, minimalist design, value annotations, external legends._

---

## 🚀 Insights and Findings

- Overall adoption rate increased by ~12% from 2023 to 2024.
- **Technology**, **Marketing**, and **Finance** are projected to have the highest adoption rates by 2025.
- **Healthcare** and **Legal** sectors show slower but steady growth.
- KMeans clustering identified 3 major groups of industries by adoption behavior.

---

## 📚 Project Folder Structure

```
/GenerativeAI_Industry_Adoption_Analysis
    ├── README.md
    ├── Generative_AI_Industry_Adoption.csv
    ├── notebooks/
    │   ├── 01_EDA_and_Cleaning.ipynb
    │   ├── 02_Forecasting_and_Trend_Analysis.ipynb
    │   ├── 03_Feature_Engineering.ipynb
    │   └── 04_Clustering_Analysis.ipynb
    └── plots/
        ├── adoption_distribution.png
        ├── forecast_trend_2025.png
        ├── industry_growth_comparison.png
        ├── outlier_boxplot.png
        └── clustering_result.png
```

---

## 💬 How to Run

1. Clone the repository:
    ```
    git clone https://github.com/yourusername/GenerativeAI_Industry_Adoption_Analysis.git
    ```
2. Install dependencies:
    ```
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
3. Open the Jupyter notebooks inside the `/notebooks` folder.
4. Run the code step-by-step!

---

## 👨‍💼 Author

- **[Bhavagna Shreya Bandaru]**
- 📫 Contact: [bbandar5@asu.edu]  


---

# 🎯 Final Words

This project showcases not just raw data analysis,  
but **professional-level storytelling**, **forecasting**, and **predictive thinking**.  

> **"Data is the fuel. Insight is the engine." 🚀**

