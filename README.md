# Health Survey Data Analyzer 

This is a beginner-friendly data analysis project using real-world health data from the NHANES survey.  
The script loads BMI and demographic data, classifies BMI categories, and visualizes distributions — including by gender and age group.

---

## 📁 Files Included

- `analyzer.py` — Main analysis script
- `nhanes_bmi_male.csv` — BMI data (males, from NHANES 2015–2018)
- `nhanes_bmi_female.csv` — BMI data (females, from NHANES 2015–2018)
- `README.md` — Project overview

---

## 📊 What the script does

- Loads and combines real NHANES BMI data
- Classifies BMI as Underweight, Normal, Overweight, or Obese
- Groups by age ranges (18–29, 30–44, 45–59, 60+)
- Visualizes:
  - BMI distribution overall
  - BMI distribution by gender

---

## ▶️ How to Run

Make sure you have **Python 3** and the required packages:

```bash
pip install pandas matplotlib

