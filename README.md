***📊 Data Science Project Using R***
This repository contains solutions to a variety of data analysis problems using R, covering topics such as data wrangling, filtering, aggregation, string manipulation, date parsing, and more.

***📁 Dataset***
The dataset used in this project contains customer-level information including:

Customer profession
Gender
Phone and email
Province and country
Credit card details
Purchase information
Dates of transactions
***✅ Tasks Completed***
***🔍 Data Exploration and Filtering***
Filtered customers with duplicate phone numbers
Found how many customers belong to the profession "Structural Engineer"
Counted how many male Structural Engineers exist
Filtered female Structural Engineers from Alberta (AB)
Identified customers who did not spend anything and need a deal
***💳 Credit Card Analysis***
Extracted and parsed credit card expiration dates using lubridate::my()
Counted how many cards expire in 2019
Found how many customers use Visa as their card provider
Identified customers who spent exactly 100 CAD using Visa
Counted how many emails are associated with a specific credit card number
***📧 Email Analysis***
Extracted the top 5 most common email providers using stringr::str_extract() and str_split_fixed()
Checked if any customers use emails with domain "am.edu"
***📆 Date and Time Analysis***
Parsed purchase date using lubridate::mdy()
Identified the day of the week with the highest number of customers (e.g., Tuesday)
***🧰 R Packages Used***
dplyr: Data manipulation (filtering, grouping, summarizing)
stringr: String extraction and pattern matching
lubridate: Date conversion and parsing
