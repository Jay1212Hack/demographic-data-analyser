# 📊 Demographic Data Analyzer

This project is part of the **freeCodeCamp Data Analysis with Python** curriculum.

It analyzes a dataset from the 1994 U.S. Census database using **Pandas** and answers several demographic questions, such as:

- Race representation
- Average age of men
- Education level vs salary
- Working hours vs income
- Country-wise income statistics
- Most common high-income occupations

---

## 🗂 Dataset

The dataset used is `adult.data.csv` from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/adult).

---

## 🧠 What the Script Calculates

The `calculate_demographic_data()` function answers:

- 📌 Count of people by race
- 👨 Average age of men
- 🎓 % with a Bachelor's degree
- 🧠 % with advanced education (`Bachelors`, `Masters`, `Doctorate`) earning >50K
- 📘 % without advanced education earning >50K
- ⏱ Minimum working hours per week
- 💰 % of people who work minimum hours and earn >50K
- 🌍 Country with highest % of high earners and the percentage
- 🇮🇳 Top occupation in India for those earning >50K

---

## 🛠 How to Run

### 1. Install Requirements

```bash
pip install pandas
