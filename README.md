# Exploratory Data Analysis of Global Developer Survey Data

## Project Overview
This project presents a comprehensive Exploratory Data Analysis (EDA) of the Stack Overflow Global Developer Survey dataset (49,191 respondents, 172 columns). The analysis investigates global tech industry trends, educational pathways, and high-income workforce distributions across various countries and industries.

## Technical Milestones
* **Data Validation & Integrity:** Checked unique response identifiers ensuring zero duplicate records and used Python sets intersection to perfectly align responses with the official question schema dataset.
* **Descriptive Statistics:** Extracted professional experience benchmarks (mean, median, mode) using customized lambda aggregation functions in Pandas.
* **Demographic & Tech Segmentation:** Created analytical data masks to isolate Python developers and analyzed technology adoption rates across distinct age cohorts.
* **Advanced Market Analytics:** Applied mathematical filtering using the 75th percentile (`.quantile(0.75)`) to isolate top-25% high-earning remote professionals and evaluated their concentration across employment sectors using `.value_counts`.

## Key Findings
* **Python Popularity:** 37.5% of global developers utilize Python, with adoption peaking at 40% in the 18-24 age bracket.
* **Top Sectors for Remote Talents:** Software Development, Fintech, and Healthcare emerged as the dominant high-paying industries for premium remote tech professionals.
* **Education Trends:** Online courses stand out as a major educational driver, with 10,973 individuals using them to learn how to code.
