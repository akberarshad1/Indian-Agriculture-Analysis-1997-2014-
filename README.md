# 🌾 Indian Agriculture Analytics

An end-to-end data analytics project that explores Indian agricultural crop production across states, districts, crops, and seasons using Python, Pandas, NumPy, Matplotlib, and Power BI.

## 📌 Project Overview

This project analyzes historical Indian crop production data to identify agricultural trends, compare crop production across states, examine seasonal patterns, and understand the relationship between cultivated area and production.

The project combines Python-based data cleaning and exploratory data analysis (EDA) with interactive Power BI dashboards to transform raw agricultural data into meaningful insights.

## 🎯 Objectives

- Analyze crop production trends across different years.
- Identify top-performing and low-performing states.
- Compare crop production across different seasons.
- Explore crop-wise and state-wise agricultural patterns.
- Analyze the relationship between cultivated area and production.
- Build interactive dashboards for agricultural data exploration.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data analysis |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Jupyter Notebook | Exploratory data analysis |
| Power BI | Interactive dashboards |

## 📂 Project Structure

```text
Indian-Agriculture-Analytics/
│
├── data/
│   ├── raw/
│   │   └── crop_production.csv
│   └── processed/
│       └── crop_production_powerbi.csv
│
├── notebooks/
│   └── agriculture_analysis.ipynb
│
├── visuals/
│   └── agriculture_dashboard.png
│
├── powerbi/
│   └── agriculture_dashboard.pbix
│
└── README.md
```

## 📊 Dataset Information

**Dataset:** Crop Production in India

**Source:** [Kaggle - Crop Production in India](https://www.kaggle.com/datasets/abhinand05/crop-production-in-india)

The dataset contains historical agricultural information, including:

- State Name
- District Name
- Crop Year
- Season
- Crop
- Area
- Production

**Analysis Period:** 1997–2014

The year 2015 was excluded from nationwide comparisons because its dataset coverage was incomplete.

## 🔍 Project Workflow

1. **Data Collection:** Obtained the Indian crop production dataset from Kaggle.
2. **Data Cleaning:** Inspected missing values, duplicates, and inconsistent entries.
3. **Data Processing:** Prepared the dataset for analysis and visualization.
4. **Exploratory Data Analysis:** Examined crop, state, district, and seasonal production patterns.
5. **Data Visualization:** Created charts using Matplotlib.
6. **Power BI Dashboard:** Developed interactive dashboards to explore agricultural trends.

## 📈 Key Analysis Areas

- Year-wise crop production trends
- State-wise crop production comparison
- Top 5 and bottom 5 producing states
- Crop-wise production analysis
- Seasonal production distribution
- Area vs. production relationship
- Crop yield analysis
- Geographical distribution of crop production

## 📊 Dashboard

The Power BI dashboard provides interactive visualizations to explore agricultural production data.

**Dashboard features include:**
- KPI cards
- Yearly production trend
- Crop and season analysis
- State-wise production comparison
- India map visualization
- Interactive filters and slicers

## 💡 Key Insights

The analysis explores:

- Changes in agricultural production over time.
- Differences in crop production across Indian states.
- Seasonal variations in crop production.
- States with the highest and lowest production for selected crops.
- Relationships between cultivated area and agricultural output.

*Note: Production values across different crops should be interpreted carefully because measurement units may vary by crop.*

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/akberarshad1/Indian-Agriculture-Analysis-1997-2014-
```

2. Navigate to the project directory:

```bash
cd Indian-Agriculture-Analytics
```

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. Launch Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `agriculture_analysis.ipynb` and run the cells.

To explore the Power BI dashboard, open the `.pbix` file using Power BI Desktop.

## 🔮 Future Enhancements

- Integrate more recent agricultural datasets.
- Add rainfall and climate data for deeper analysis.
- Develop crop production prediction models using Machine Learning.
- Build a web-based dashboard using Streamlit.
- Explore district-level agricultural performance.

## 👨‍💻 Author

**Akber Mohammed Arshad**

- GitHub: [akberarshad1](https://github.com/akberarshad1)
- LinkedIn: [Akber Arshad](https://www.linkedin.com/in/akber-arshad-59a6b0245/)

---

⭐ If you find this project interesting, consider giving the repository a star!
