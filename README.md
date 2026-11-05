# 😊 World Happiness Report Analysis

**Developed By:** Jenisha Ramani

## 📌 Project Description

The World Happiness Report Analysis is a Python-based data analysis project that explores country-level happiness data using NumPy, Pandas, Matplotlib, and Seaborn in a Jupyter Notebook.

It provides useful insights about happiness scores across countries, yearly happiness trends, the relationship between happiness and factors like GDP, social support, and life expectancy, and groups countries into happiness categories.

## ✨ Features

- CSV Data Loading
- Data Cleaning and Preprocessing
- Duplicate Removal (Country + Year)
- Missing Value Check
- Date Column Creation from Year
- Summary Statistics
- Correlation Analysis
- Country Ranking by Average Happiness
- Yearly Happiness Trend Analysis
- Country Segmentation (High / Medium / Low Happiness)
- Data Visualization using Matplotlib and Seaborn

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn

## 📁 Project Structure

```text
world_happiness_project/
│
├── main.ipynb
├── world_happiness_report.csv
├── heatmap.png
├── top_countries_happiness.png
├── yearly_happiness_trend.png
├── scatter_plot.png
└── README.md
```

## 🗂️ Dataset Information

- **Rows / Columns:** 999 rows and 24 columns (199 rows after removing duplicates)
- **Countries (10):** Australia, Brazil, Canada, China, France, Germany, India, South Africa, UK, USA
- **Years:** 2005 to 2024
- **Main Columns:** Happiness_Score, GDP_per_Capita, Social_Support, Healthy_Life_Expectancy, Freedom, Generosity
- **Other Columns:** Corruption_Perception, Unemployment_Rate, Education_Index, Population, Urbanization_Rate, Life_Satisfaction, Public_Trust, Mental_Health_Index, Income_Inequality, Public_Health_Expenditure, Climate_Index, Work_Life_Balance, Internet_Access, Crime_Rate, Political_Stability, Employment_Rate

## 🚀 How to Run

**1. Install required libraries**

```bash
pip install numpy pandas matplotlib seaborn jupyter
```

**2. Keep the notebook and CSV file in the same folder**

```text
main.ipynb
world_happiness_report.csv
```

**3. Open the notebook**

```bash
jupyter notebook main.ipynb
```

**4. Run all cells from top to bottom.**

The charts will be saved as PNG files in the same folder.

---

## 📊 Visualizations

The project generates four charts:

1. **Heatmap:** Correlation Matrix for Main Features
2. **Bar Chart:** Top 5 Countries by Average Happiness Score
3. **Line Chart:** Yearly Happiness Score Trend
4. **Scatter Plot:** Country Happiness Segmentation (High / Medium / Low)
