# EDA_Portfolio

This project was completed as part of a data science learning exercise, with a focus on:
- Practicing **data cleaning** and **feature engineering**
- Handling **messy real-world text data** (Crore/Lakh/Thousand, Marla/Kanal, etc.)
- Building **basic visualizations** to support real-estate investment decisions

---

## 🔍 Project Objective

The goal of this project is to analyze property listings from Zameen.com and generate **actionable insights** for investors and stakeholders.

Key questions:

- What drives **property prices** in major cities of Pakistan?
- How do prices compare across **cities** and **property types**?
- How can we use **price per square foot** to compare deals more fairly?
- Which cities appear more **premium** or more **affordable** based on the data?

---

## 🧾 Dataset

The dataset contains scraped listings from Zameen.com with features such as:

- `City`, `Location`
- `Price` (e.g. `PKR\n4.75 Crore`, `PKR\n65 Lakh`)
- `Area` (e.g. `5 Marla`, `1 Kanal`, `128 Sq. Yd.`)
- `Type` (House, Flat, Plot, etc.)
- `Bedrooms`, `Bathrooms`
- `Purpose` (For Sale / For Rent)
- Various amenities (e.g. parking, flooring, internet, etc.)

In this repo, the dataset is stored as:

```text
data/
└── Scarped Zameen.com.xlsx - Sheet1.csv
