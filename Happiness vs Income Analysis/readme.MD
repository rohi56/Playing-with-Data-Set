# 📊 Happiness vs Income Analysis

This project explores the relationship between **Happiness Score** and **GDP per Capita** using global data from 111 countries. The goal is to determine whether richer countries are necessarily happier and to highlight outliers that don't follow the general trend.

## 🔍 Overview

Using data visualization and analysis, this notebook seeks to answer:
- Do higher-income countries report higher happiness?
- Which countries stand out from the trend (either happier or less happy than expected)?
- What might explain these outliers?

## 📁 Dataset

- **Source:** `happyscore_income.csv`
- **Columns Used:**
  - `country`: Name of the country
  - `GDP`: GDP per capita
  - `happyScore`: Happiness score (typically from the World Happiness Report)
  - `region`: Geopolitical region of the country

## 📊 Visualization

- A **scatter plot** visualizes the relationship between **GDP per Capita** (X-axis) and **Happiness Score** (Y-axis).
- Countries are **colored by region**.
- Countries with:
  - Happiness scores **above 7.5** (e.g., Norway, Switzerland)
  - Happiness scores **below 4.5** (e.g., Syria, Burundi)  
  are **highlighted with labels** for easy identification.

## 💡 Key Observations

- Wealthier countries generally report higher happiness.
- Some countries with **moderate GDPs** (e.g., **Costa Rica**) report **high happiness**, suggesting **non-economic factors** like governance, community, and freedom play major roles.
- Countries with very **low happiness scores** often face **political instability or economic crisis**.

## 🛠️ Tools Used

- **Python 3**
- **Pandas** for data manipulation
- **Seaborn** and **Matplotlib** for data visualization

## 📌 How to Run

1. Ensure the following files are in your working directory:
   - `Happiness_vs_Income_Analysis.ipynb`
   - `happyscore_income.csv`
2. Open the notebook in Jupyter or VS Code.
3. Run the cells in order to reproduce the analysis and plots.

## 📈 Example Plot

> *Scatter plot: Happiness Score vs GDP per Capita, labeled with extreme cases.*

## 📬 Conclusion

While GDP is a strong indicator of a country’s happiness, it's not the only one. Factors such as freedom, safety, social support, and governance quality are crucial in shaping a nation’s well-being.
