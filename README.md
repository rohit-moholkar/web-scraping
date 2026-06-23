## WEB SCRAPING PORTFOLIO

This repository contains Python web scraping projects focused on collecting, parsing, cleaning, and structuring real-world web data. The projects demonstrate data extraction and data wrangling from e-commerce websites, static web pages, dynamic tables, and online data sources using Requests, BeautifulSoup, Selenium, and Pandas. The repository combines e-commerce scraping projects and tabular data scraping projects into one organized portfolio.

## 📌 Project Highlights

| Project | Category | Source | Records | Key Output |
|---|---|---|---:|---|
| [Flipkart Mobile Listings](ecommerce-scraping/flipkart-mobile-listings) | E-commerce scraping | Flipkart | 984 | Mobile listings with price, discount, ratings, reviews, RAM/ROM, display, camera, and battery details |
| [Campus Footwear Listings](ecommerce-scraping/campus-footwear-listings) | E-commerce scraping | Campus Footwear | 263 | Product descriptions, MRP, and current prices |
| [Box Office Mojo Top Movies](tabular-data-scraping/box-office-mojo-top-movies) | Tabular data scraping | Box Office Mojo | 200 | Movie rank, title, lifetime gross, and release year |
| [Asian Games Medal Table](tabular-data-scraping/asian-games-medal-table) | Tabular data scraping | JagranJosh | 41 | Country-wise gold, silver, bronze, and total medal counts |
| [NSE Midcap Companies](tabular-data-scraping/nse-midcap-companies) | Dynamic table scraping | Moneycontrol | 100 | Company name, LTP, percentage change, volume, buy/sell price, and quantity |
| [CWC Qualifier Batting Stats](tabular-data-scraping/cwc-qualifier-batting-stats) | Tabular data scraping | Moneycontrol CricketWorld | 80 | Player batting statistics including runs, average, strike rate, centuries, boundaries, and matches |
| [Tokyo Olympics Medal Table](tabular-data-scraping/tokyo-olympics-medal-table) | Tabular data scraping | BBC Sport | 93 | Country-wise Olympic medal table with gold, silver, bronze, and total medals |

## 📂 Repository Structure

```text
web-scraping/
├── README.md
├── requirements.txt
├── .gitignore
├── ecommerce-scraping/
│   ├── flipkart-mobile-listings/
│   │   ├── flipkart_mobile_listings_scraping.ipynb
│   │   ├── data/
│   │   │   └── flipkart_mobile_listings.csv
│   │   └── documents/
│   │       └── flipkart_mobile_listings_report.pdf
│   └── campus-footwear-listings/
│       ├── campus_footwear_listings_scraping.ipynb
│       ├── data/
│       │   └── campus_footwear_listings.csv
│       └── documents/
│           └── campus_footwear_listings_report.pdf
└── tabular-data-scraping/
    ├── box-office-mojo-top-movies/
    │   ├── box_office_mojo_top_movies_scraping.ipynb
    │   └── data/
    │       └── box_office_mojo_top_movies.csv
    ├── asian-games-medal-table/
    │   ├── asian_games_medal_table_scraping.ipynb
    │   └── data/
    │       └── asian_games_medal_table.csv
    ├── nse-midcap-companies/
    │   ├── nse_midcap_companies_scraping.ipynb
    │   └── data/
    │       └── nse_midcap_companies.csv
    ├── cwc-qualifier-batting-stats/
    │   ├── cwc_qualifier_batting_stats_scraping.ipynb
    │   └── data/
    │       └── cwc_qualifier_batting_stats.csv
    └── tokyo-olympics-medal-table/
        ├── tokyo_olympics_medal_table_scraping.ipynb
        └── data/
            └── tokyo_olympics_medal_table.csv
```

## 🧩 Skills Demonstrated

- Web scraping with Python
- HTML parsing using BeautifulSoup
- HTTP requests using Requests
- Browser automation using Selenium
- Static and dynamic website data extraction
- Tabular data extraction
- Pagination handling
- Data cleaning and preparation
- Data wrangling and structuring
- Pandas DataFrame creation
- CSV data export
- Organized project documentation

## 💻 Technology Stack

- Python
- Jupyter Notebook
- Pandas
- Requests
- BeautifulSoup
- Selenium
- CSV

## 📚 Project Categories

### E-commerce Scraping

The e-commerce scraping projects focus on collecting, cleaning, and structuring product-level information from online retail websites. These projects demonstrate multipage scraping, product attribute extraction, price collection, discount tracking, data preparation, and structured dataset creation.

### Tabular Data Scraping

The tabular data scraping projects focus on extracting, preparing, and formatting structured tables from websites across movies, sports, finance, and international events. These projects demonstrate table parsing, dynamic table extraction, data cleaning, data formatting, and CSV export.

## ▶️ Running the Notebooks

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Open any project notebook using Jupyter Notebook or VS Code:

```bash
jupyter notebook
```

Some websites may update their structure over time, so live scraping results may differ from the saved datasets included in this repository.

## 🚀 Purpose

The purpose of this repository is to present practical web scraping projects in a clean, structured, and well-documented format. These projects demonstrate how real-world web data can be collected, parsed, cleaned, prepared, and transformed into structured datasets for further analysis, reporting, and business use cases.
