# 📊 Data Science Project Using R

This repository showcases a comprehensive data analysis project conducted using **R** and **Quarto Markdown (.qmd)**. The analysis focuses on exploring and extracting actionable insights from customer data using data wrangling, string manipulation, date parsing, and visualization techniques. The `.qmd` file was rendered to a clean and interactive **HTML report**, providing an accessible summary of the results.

---

## 📁 Dataset Overview

The dataset includes customer-level information such as:

* Profession
* Gender
* Phone number and email address
* Province and country
* Credit card details
* Purchase amounts
* Transaction dates

---

## ✅ Tasks Completed

### 🔍 Data Exploration & Filtering

* Filtered customers with **duplicate phone numbers**
* Counted how many customers belong to the profession **"Structural Engineer"**
* Determined the number of **male Structural Engineers**
* Filtered **female Structural Engineers from Alberta (AB)**
* Identified customers who **did not spend anything** and may benefit from targeted promotions

### 💳 Credit Card Analysis

* Parsed credit card expiration dates using `lubridate::my()`
* Counted how many cards **expire in 2019**
* Found customers using **Visa** as their card provider
* Filtered customers who **spent exactly 100 CAD using Visa**
* Counted emails **associated with specific credit card numbers**

### 📧 Email Analysis

* Extracted the **top 5 most common email providers** using `stringr::str_extract()` and `str_split_fixed()`
* Checked if any customers use email domains like **"am.edu"**

### 📆 Date & Time Analysis

* Parsed purchase dates with `lubridate::mdy()`
* Identified the **day of the week** with the highest number of purchases (e.g., **Tuesday**)

---

## 🧰 Tools & Packages Used

* **Quarto Markdown (.qmd)** – Used to create an R-based report, rendered to HTML as an alternative to LaTeX
* **dplyr** – Data manipulation (filtering, grouping, summarizing)
* **stringr** – String extraction and pattern matching
* **lubridate** – Date parsing and conversion
* **readr / tibble** – For structured and tidy data handling

---

## 📌 Purpose

This project demonstrates the power of **R** and **Quarto** for data science workflows—from analysis to report generation. It highlights how tidyverse packages can be used to gain insights into customer behavior and provide data-driven support for marketing and product strategies.

---
