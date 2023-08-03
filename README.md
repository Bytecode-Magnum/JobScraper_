# Project Title
Data Scientist Jobs Web Scraper from Naukri.com

## Project Description
This project is a Python-based web scraper designed to gather valuable data scientist job listings from naukri.com, a popular job portal. By utilizing HTTP requests, managing cookies and headers, parsing JSON data, and finally storing the extracted job details in a CSV file, this tool simplifies the process of collecting job information for data science enthusiasts and job seekers.

[Scraper](https://github.com/Bytecode-Magnum/JobScraper_/blob/main/JobScraper.ipynb)


## Required Python libraries: 
List the libraries here, e.g.,
 
requests

json

pandas


## Configuration
In the scraper.py file, you'll find a few variables that might require adjustment according to your preferences:

URL: This should be the URL of the naukri.com job listings page you wish to scrape.

COOKIES: Replace this with the cookies obtained from your browser's network tab after logging into naukri.com.

HEADERS: Adjust these headers to replicate a genuine browser request.

## Output
The collected job data will be organized and saved in a CSV file named jobs.csv. This CSV file will consist of the following columns:

Job Title

Salary

Job_ID

Experience

Salary

Preferred Location

Job Description

Posted On

[Output_Data](https://github.com/Bytecode-Magnum/JobScraper_/blob/main/Jobs.csv)
