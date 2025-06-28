# 📊 Dataset Description: Statlog (German Credit Data)

## 🔗 Source
- UCI Machine Learning Repository  
- [Statlog (German Credit Data)](https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data)

## 📄 Overview
The dataset classifies people described by a set of attributes as **good or bad credit risks**.  
It contains **1000 entries** with **20 features** and **1 target variable**.

---

## 📁 Features

| Feature Name               | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| `Status_Checking_Acc`     | Status of existing checking account                                         |
| `Duration`                | Duration in months                                                          |
| `Credit_History`          | Credit history (e.g., critical, existing paid)                              |
| `Purpose`                 | Purpose of credit (e.g., car, furniture, radio/TV)                          |
| `Credit_Amount`           | Amount of credit in Deutsche Marks                                          |
| `Savings_Account`         | Savings account/bonds status                                                |
| `Employment`              | Present employment since (years)                                            |
| `Installment_Rate`        | Installment rate in percentage of disposable income                         |
| `Personal_Status`         | Personal status and sex                                                     |
| `Other_Debtors`           | Other debtors / guarantors                                                  |
| `Residence_Since`         | Duration in current address (years)                                         |
| `Property`                | Type of property (real estate, savings, etc.)                               |
| `Age`                     | Age in years                                                                |
| `Other_Installment_Plans` | Other installment plans (bank, stores, none)                                |
| `Housing`                 | Type of housing (own, rent, for free)                                       |
| `Existing_Credits`        | Number of existing credits at this bank                                     |
| `Job`                     | Job type (unskilled, skilled, management, etc.)                             |
| `Num_People_Maintained`   | Number of people being maintained by the applicant                          |
| `Telephone`               | Whether the customer has a telephone                                        |
| `Foreign_Worker`          | Whether the person is a foreign worker                                      |

---

## 🎯 Target Variable

| Target Variable | Description               |
|-----------------|---------------------------|
| `Credit_Risk`   | 1 = Good, 0 = Bad customer |

---

## 🧹 Preprocessing Notes

- Categorical variables were **label encoded** using `LabelEncoder`.
- Target was mapped from `{1: Good, 2: Bad}` to `{1: Good, 0: Bad}`.

---

## 📌 Example Record

| Age | Credit Amount | Job | Housing | Credit Risk |
|-----|----------------|-----|---------|--------------|
| 35  | 2100           | 2   | 1       | 1 (Good)     |
