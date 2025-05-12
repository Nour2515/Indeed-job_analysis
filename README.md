# 💼 Indeed Job Scraper & Analyzer

This project scrapes job listings from **Indeed.com** using Selenium, saves them in a CSV file, then performs data cleaning, analysis, and visualization using **Pandas**, **Seaborn**, and **Matplotlib**.

## 📌 Features

- 🔍 Scrapes job listings with details like:
  - Job Title
  - Location
  - Company
  - Job Type
  - Pay
  - Company Rating
- 💾 Saves data to `indeed_jobs.csv`
- 🧹 Cleans and preprocesses the data (removes duplicates, handles missing values, processes salary ranges)
- 📊 Analyzes:
  - Most common job titles
  - Average salaries per company
  - Salaries vs. company ratings
  - Top locations by salary and number of jobs
- 📈 Visualizes key insights using pie charts, bar plots, and scatter plots

---

## 🛠️ Requirements

Install the dependencies using `pip`:

```bash
pip install selenium pandas matplotlib seaborn webdriver-manager
