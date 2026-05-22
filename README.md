# 🦠 COVID-19 Global Trends — Exploratory Data Analysis

> *"Numbers speak. My job is to make their story heard."*

A visual and statistical analysis of COVID-19 global data using Python and Google Colab, focusing on comparing total deaths, death rates, and time-series behavior across countries.

---

## 📌 Project Overview

This project goes beyond surface-level numbers to explore **what the data actually tells us** about the pandemic's impact — distinguishing between absolute counts and proportional severity, and testing whether COVID-19 case trends follow predictable patterns.

**Dataset:** [Our World in Data — COVID-19](https://ourworldindata.org/coronavirus)

---

## 🎯 Analysis Goals

1. **Distinguish** between absolute death counts and death rates (Deaths / Confirmed Cases) as measures of severity.
2. **Identify** countries that successfully contained the pandemic despite high case numbers.
3. **Highlight** the role of healthcare infrastructure and response speed in outcomes.
4. **Test** whether the daily new cases time series follows a Random Walk — a key indicator of predictability and potential for forecasting models.

---

## 📂 Project Contents

- Statistical analysis of the **Top 10 countries by total deaths**
- Comparison of **death rates** across nations
- Visualizations illustrating differences between countries
- Critical reading of how raw numbers relate to the true scale of impact
- **ADF (Augmented Dickey-Fuller) statistical test** applied to US daily new cases

---

## 🔍 Key Finding

> After applying the **ADF statistical test**, US daily new case data was found to **not follow a Random Walk**.
>
> This means the data contains **structural patterns** that can be leveraged to build predictive forecasting models — a significant insight for epidemiological planning.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas | Data loading and manipulation |
| Matplotlib & Seaborn | Data visualization |
| Statsmodels | ADF statistical testing |
| Google Colab | Development environment |

---

## 🚀 How to Run

1. Open `covid19_analysis.ipynb` in [Google Colab](https://colab.research.google.com/)
2. Install required libraries:
```bash
pip install pandas matplotlib seaborn statsmodels
```
3. Run all cells sequentially

---

## 📊 Sample Outputs

- Top 10 countries by total deaths
- Top 10 countries by death rate
- Countries with lowest death rates
- ADF test results for US time-series data

---

## 👩‍💻 About

**Salma Alyossef** — Data Analyst passionate about transforming raw numbers into actionable insights and real-world stories.

📌 [LinkedIn](https://www.linkedin.com/in/salma-alyossef-586a951ab) | [GitHub](https://github.com/Salma-yossef-analytics)
