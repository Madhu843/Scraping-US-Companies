# 🏢 Web Scraping: Largest U.S. Companies by Revenue

This project demonstrates how to scrape the **List of largest companies in the United States by revenue** from [Wikipedia](https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue) using `BeautifulSoup` and `pandas`.

## 📌 Objective

- Extract tabular data of top U.S. companies by revenue.
- Clean and structure the data into a pandas DataFrame.
- Handle row mismatch issues using a data validation check.

## 📁 Files

- `Scraping Data Project.ipynb` – Jupyter notebook with full scraping workflow.
- `requirements.txt` – Python libraries used.
- `README.md` – Project overview.

## 🔍 Key Highlights

- Uses `requests` and `BeautifulSoup` to pull HTML data.
- Parses the table of companies, cleaning whitespace and validating row length.
- Appends valid rows into a pandas DataFrame.

## 🔧 Libraries Required

```bash
pandas
beautifulsoup4
requests
