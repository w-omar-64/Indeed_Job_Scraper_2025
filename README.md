# **Indeed Job Scraper **

## **Overview**
This notebook is a web scraper for Indeed job postings, built using **Selenium** and **BeautifulSoup (bs4)**. It automates the process of searching for job listings, extracts relevant details (such as job title, company, location, and link), and saves the data into a CSV file for further analysis.

## **Features**
- ✅ Automates job searches on [Indeed](https://www.ca.indeed.com/)
- ✅ Uses **Selenium** for dynamic page navigation
- ✅ Parses job details with **BeautifulSoup**
- ✅ Saves extracted job postings into a **CSV file**
- ✅ Customizable search parameters (keywords, location)

## **Requirements**
Ensure you have the following installed:
- **Python 3.x**
- **Selenium**
- **BeautifulSoup (bs4)**
- **Pandas**
- **WebDriver** (ChromeDriver for Google Chrome)
---

## **Usage**
### **1. Set Up WebDriver**
- Download and install the WebDriver for your browser.
- Ensure the WebDriver path is correctly configured in the script.

### **2. Define Job Search Parameters**
- Modify search keywords and location.

### **3. Scrape Job Data**
- The script will visit **Indeed**, search for jobs, and extract details such as:
  - Job title  
  - Company name  
  - Job location  
  - link
  - 
### **4. Save Results to CSV**
- The extracted job listings are saved as `indeed_jobs.csv`.
- You can open the CSV file in Excel, Google Sheets, or load it into Pandas for further analysis.

## **Disclaimer**
> **⚠️ Educational Purposes Only**  
> This scraper is for **educational purposes only**.
---
🚀 Happy Scraping!  
