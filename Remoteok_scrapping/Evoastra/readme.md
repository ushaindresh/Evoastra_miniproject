# 🌍 Remote Job Market Intelligence – Ethical Web Scraping Project

# 🏢 Organization  
Evoastra Ventures (OPC) Pvt Ltd


## 📖 Project Overview  
This project focuses on building an end-to-end data pipeline to analyze the **remote job market** using **ethical web scraping** techniques.

The goal is to extract publicly available job listings from RemoteOK, clean and process the data, and generate **market intelligence insights** such as skill demand, popular job roles, and job type distribution.

All scraping activities strictly follow ethical, legal, and compliance guidelines.

## 🌐 Target Website  
https://remoteok.com

## 🎯 Project Objectives  
- Ethically scrape job listings from RemoteOK  
- Respect robots.txt and server rate limits  
- Clean and normalize raw scraped data  
- Perform exploratory data analysis (EDA)  
- Create business-ready visualizations  
- Document the entire workflow professionally  

## ⚖️ Ethical & Legal Compliance  
This project strictly adheres to ethical web scraping practices:

- Followed robots.txt rules  
- Implemented 1-second crawl delay between requests  
- Avoided forbidden endpoints (e.g. `?action=get_jobs`)  
- No aggressive or parallel scraping  
- Raw scraped data is not shared publicly  
- Data used only for educational and analytical purposes  

## 🛠️ Tools & Technologies Used  
- Python 3.8+  
- Requests  
- BeautifulSoup (bs4)  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

### 1️⃣ Web Scraping  
- Scraped job listings from RemoteOK public HTML pages  
- Extracted:
  - Job Title  
  - Company Name  
  - Skills / Tags  
  - Job Type  
  - Location  
  - Date Posted  
  - Job URL  

**File:** `scraper.ipynb`

### 2️⃣ Data Cleaning  
- Removed duplicate records  
- Handled missing values  
- Normalized text data  
- Standardized skill tags  
- Prepared final cleaned dataset  

**File:** `Data_Cleaning.ipynb`


### 3️⃣ Data Analysis & Visualization  
The following visualizations were created:

- Top 10 Most Demanded Skills  
- Job Type Distribution (Full-time vs Contract)  
- Top Job Titles in the Remote Market  
- Skill Frequency Comparison  
- Location-wise Job Distribution  

Each visualization answers a specific business question and is properly labeled.

**File:** `analyzer.ipynb`

## 📊 Key Insights  
- Certain technical skills dominate the remote job market  
- Full-time roles form a major portion of remote jobs  
- Specific job titles appear consistently across postings  
- Skill demand shows strong concentration  
- Hiring trends vary across regions and companies  


## ▶️ How to Run the Project  

1. Install dependencies  
```bash
pip install -r requirements.txt
```

2. Run scraping notebook
```bash
scraper.ipynb
```

3. Clean the data
```bash
Data_Cleaning.ipynb
```

4. Generate analysis and visualizations
```bash
analyzer.ipynb
```
