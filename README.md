# Alibaba_Web_scraping
🕸️ Alibaba RFQ Web Scraper
This project scrapes Request for Quotation (RFQ) listings from Alibaba's sourcing platform using Selenium with multi-threaded scraping for performance. It collects detailed information from each RFQ card, including metadata like buyer name, country, quantity required, inquiry time, and more.

🚀 Features
Extracts detailed data from multiple RFQ pages

Parallel scraping using Python’s ThreadPoolExecutor

Automatic pagination handling

Cleans and processes extracted data

Saves both raw and cleaned data to CSV files

Supports headless Chrome scraping for performance

Dynamically calculates total available RFQ pages

📌 Scraped Fields
RFQ ID

Title

Buyer Name

Buyer Image

Inquiry Time

Quotes Left

Country

Quantity Required

Email Confirmed

Experienced Buyer

Complete Order via RFQ

Typical Replies

Interactive User

Inquiry URL

Inquiry Date

Scraping Date

🧱 Tech Stack
Python 3.10+

Selenium

WebDriver Manager

Pandas

ThreadPoolExecutor (for multithreading)

Google Colab / Jupyter Notebook compatible

