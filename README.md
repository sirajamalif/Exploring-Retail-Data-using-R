# 📊 Data Science Project Using R

This repository showcases a comprehensive data analysis project conducted using R. The project involves exploring and extracting meaningful insights from a customer dataset through various data wrangling, transformation, and analysis techniques.

---

## 📁 Dataset Overview

The dataset contains customer-level information, including:

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
* Counted the number of customers in the **"Structural Engineer"** profession
* Determined the number of **male Structural Engineers**
* Filtered **female Structural Engineers from Alberta (AB)**
* Identified customers who **did not spend anything** and may need targeted offers

### 💳 Credit Card Analysis

* Extracted credit card expiration dates using `lubridate::my()`
* Counted credit cards that **expire in 2019**
* Identified customers using **Visa** as their card provider
* Filtered customers who **spent exactly 100 CAD using Visa**
* Counted emails **linked to a specific credit card number**

### 📧 Email Analysis

* Extracted the **top 5 most common email providers** using `stringr::str_extract()` and `str_split_fixed()`
* Checked for customers with emails from the domain **"am.edu"**

### 📆 Date & Time Analysis

* Parsed purchase dates using `lubridate::mdy()`
* Determined the **day of the week with the highest number of customers** (e.g., Tuesday)

---

## 🧰 R Packages Used

* **dplyr** – For data manipulation: filtering, grouping, summarizing
* **stringr** – For string extraction, pattern matching, and domain analysis
* **lubridate** – For parsing and handling dates and times

---

## 📌 Purpose

This project demonstrates practical applications of R in handling real-world data, especially for customer segmentation, behavior analysis, and promotional targeting. It highlights how tidyverse tools can efficiently process and derive insights from structured datasets.

---

