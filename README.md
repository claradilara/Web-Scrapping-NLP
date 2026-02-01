# Web Scraping and Social Media Analysis Project

This project demonstrates an end-to-end **web scraping, text processing, and
sentiment analysis pipeline** implemented in Python.

The project focuses on collecting unstructured text data from the web,
cleaning and structuring it, and performing **descriptive text analytics and
sentiment analysis** to extract meaningful insights.

---

## Project Overview
The project scrapes documents from **The Black Vault** website, specifically
from the UFO-related document archive. The collected documents are processed
and analyzed to understand:
- Content characteristics
- Sentiment distribution
- Topic/category patterns

The workflow follows best practices in **ethical and responsible web scraping**,
including compliance with `robots.txt`.

---

## Data Collection (Web Scraping)
- Scraping performed using **Selenium** and **BeautifulSoup**
- Chrome WebDriver configured with user-agent masking
- Explicit waiting for dynamic elements to load
- Automatic handling of cookie consent popups
- Logging implemented to track scraping progress and errors
- Scraped data saved into uniquely named CSV files

Extracted fields include:
- Document title
- Publication date
- Full document text
- Source URL

---

## Data Cleaning & Preparation
Text preprocessing steps include:
- Lowercasing
- Removal of special characters, punctuation, numbers, and extra whitespace
- Removal of non-ASCII characters
- Tokenization and word count computation

Prepared datasets are structured for analysis and visualization.

---

## Sentiment Analysis
- Sentiment analysis performed using **TextBlob**
- Polarity-based classification:
  - Positive
  - Negative
  - Neutral
- Aggregated sentiment distributions and trends over time are visualized

Results show that **neutral sentiment dominates**, which is consistent with the
factual and report-based nature of the scraped documents.

---

## Content Categorization
Documents are categorized using **keyword-based matching** into thematic groups
such as:
- Government reports
- Military encounters
- UFO sightings
- Investigations
- Historical cases

Category distributions are visualized to identify dominant document types.

---

## Results & Insights
Key findings include:
- Strong dominance of government and official reports
- Neutral sentiment prevailing across documents
- Clear topic trends related to well-known UFO cases and investigations
- Successful transformation of unstructured web data into analyzable datasets

---

## Tools & Technologies
- Python
- Selenium
- BeautifulSoup
- pandas
- TextBlob
- matplotlib
- logging
- Jupyter Notebook

---

## Project Structure
📦 web-scraping-and-analysis/  
 ┣ Web Scrapping Project File.ipynb  
 ┣ data/  
 ┣ logs/  
 ┗ README.md  

---

## Learning Outcomes
- Ethical and robust web scraping
- Handling dynamic web content
- Text cleaning and preprocessing
- Sentiment analysis on real-world text data
- Exploratory text analytics and visualization

---

## Notes
This project was completed for academic purposes and demonstrates practical
skills in data acquisition, text analytics, and responsible web scraping.
