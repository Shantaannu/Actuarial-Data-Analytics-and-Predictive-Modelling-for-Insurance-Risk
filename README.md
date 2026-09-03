# Actuarial-Data-Analytics-and-Predictive-Modelling-for-Insurance-Risk

# Actuarial Data Analytics and Predictive Modelling for Insurance Risk

## 📌 Project Overview

This project analyses Irish private motor insurance data from the
Central Bank of Ireland's National Claims Information Database (NCID).

The project combines actuarial analysis, exploratory data analysis
and predictive modelling to investigate insurance claims, premiums
and risk over time.

The analysis focuses on aggregate insurance outcomes rather than
individual policyholder risk.

---

## 🎯 Business Problem

Insurance companies need to understand how claims and premiums change
over time to assess insurance risk, monitor claims performance and
support financial planning.

This project investigates:

- How ultimate claim costs change over time
- How frequently claims occur relative to the earned policy base
- How average ultimate claim costs change
- How ultimate claims compare with earned premiums
- Which claim types contribute most to claim costs
- Which cover types generate the most premium
- Whether historical insurance information can help predict future
  aggregate claim costs

---

## 📊 Dataset

### Source

Central Bank of Ireland — National Claims Information Database (NCID)

### Dataset

NCID Private Motor Insurance – Ultimate Claims

### Period

2010–2024

Two datasets are used in this project.

### 1. Ultimate Claims Dataset

Variables include:

- Year
- Accident Quarter
- Measure
- Claim Type
- Value

Measures include:

- Ultimate Costs
- Ultimate Numbers (incl. nils)

Claim types include:

- Accidental Damage
- Fire and Theft
- Third Party Damage
- Third Party Injury (<=250k)
- Third Party Injury (>250k)
- Third Party Injury (Total)
- Windscreen

### 2. Premium and Claims Dataset

Variables include:

- Year
- YearH
- Quarter
- Measure
- Cover Type
- Value

Measures include:

- Gross Earned Premium
- Earned Policy Count

Cover types include:

- Comprehensive
- Third Party

---

## 🗂️ Project Structure

```text
Actuarial Data Analytics/
│
├── data/
│   └── raw/
│       ├── ncid_private_motor_ultimate_claims.csv
│       └── ncid_private_motor_ultimate_prem_claims.csv
│
├── notebook/
│   ├── 01_data_exploration.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_Eda.ipynb
│   └── 05_predictive.ipynb
│
├── packages/
│   ├── __init__.py
│   └── data_import.py
│
├── Scripts/
│   └── data_cleaning.py
│
├── .gitignore
├── LICENSE
├── README.md
└── requirements.txt
