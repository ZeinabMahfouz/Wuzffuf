💼 Wuzzuf Job Scraper (Data Scientist Jobs) – Python Web Scraping Project
This Python script scrapes job listings for Data Scientist positions from Wuzzuf.net using BeautifulSoup and stores the job data in a CSV file. It collects job titles, company names, locations, job types, and job listing links.

🔍 Features
Extracts job data for "Data Scientist" roles from Wuzzuf's search page

Collects:

📌 Job Title

🏢 Company Name

📍 Location

🕒 Job Type

🔗 Job Link

Saves the collected data into a jobs.csv file

Uses requests, BeautifulSoup, and pandas

🛠️ Requirements
Python 3.x

Libraries:

requests

beautifulsoup4

pandas

lxml
📁 Output Sample (jobs.csv)
job_titles	company_names	locations	job_types
Data Scientist	XYZ Tech	Cairo, Egypt	Full Time
ML Engineer	ABC AI Labs	Remote	Part Time

Note: Links to the actual job pages are collected but not currently included in the CSV. You can easily add the links column if desired.
⚠️ Disclaimer
Wuzzuf's website structure may change over time. If the script stops working, inspect the site again to update the HTML tag/class selectors.
