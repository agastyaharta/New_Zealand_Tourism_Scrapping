## Popular Tourist Destinations in New Zealand

## Contributors 
* I Putu Agastya Harta Pratama
* Łukasz Brzoska 

Warsaw, Poland  
2025

*A Web Scraping Project on Dynamic and Static Webpages*

This project focuses on extracting structured tourism information from the official  
[New Zealand Tourism Board Website](https://www.newzealand.com/int/).  
Using a combination of **Selenium** and **BeautifulSoup**, we collected data on:

- Popular New Zealand cities to visit  
- Activity listings and categories  
- Descriptions, images, and related details  
- Contact information such as phone numbers and emails  

The goal is to build a comprehensive dataset that supports **travel planning, tourism analysis, and business intelligence** by making the rich information on the tourism board’s website more accessible for analysis.

- Many parts of the tourism website are **dynamically loaded** (e.g., search results, interactive filters).  
  These elements require **Selenium**, which controls a browser to simulate human browsing, clicks, and navigation.  
- Other sections are **static HTML** (e.g., descriptive text, fixed lists of popular cities).  
  For these, **BeautifulSoup** provides a faster and more efficient way to parse and extract information.  

---

## Project Features

- **Dynamic & Static Scraping**: Selenium for dynamic elements and BeautifulSoup for static HTML parsing.  
- **Data Collection**: City names, URLs, activities, descriptions, images, and contacts.  
- **Randomised Timing**: Simulated human-like browsing behaviour with random wait times.  
- **Reproducibility**: Data stored in pickle format for re-use and further processing.  

---

## How to Run
**Required Depedencies**
This notebook uses both **dynamic** (Selenium) and **static** (BeautifulSoup) scraping, plus standard data tooling.

**Core Python packages**
- `pandas` – tabular data handling
- `numpy` – basic numeric utilities
- `selenium` – control a real browser for dynamically loaded pages
- `beautifulsoup4` – parse static HTML fragments
- `webdriver-manager` – auto-installs the correct browser driver (GeckoDriver)
- `IPython` – display utilities inside Jupyter (e.g., images)

**System requirements**
- **Python 3.9+**
- **Jupyter** (`notebook` or `jupyterlab`)
- **Firefox browser** installed locally  
  (the notebook uses a **Firefox** driver via `webdriver-manager`; no manual driver download needed)

Simply clone the respository and run all cells consecutively! Enjoy :) 
